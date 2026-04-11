# cuda-stream

Stream processing — tumbling/sliding windows, aggregation, joins (Rust)

Part of the Cocapn fleet — a Lucineer vessel component.

## What It Does

### Key Types

- `StreamEvent` — core data structure
- `Window` — core data structure
- `WindowAgg` — core data structure
- `StreamProcessor` — core data structure
- `StreamJoiner` — core data structure

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-stream.git
cd cuda-stream

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_stream::*;

// See src/lib.rs for full API
// 8 unit tests included
```

### Available Implementations

- `StreamEvent` — see source for methods
- `Window` — see source for methods
- `StreamProcessor` — see source for methods
- `StreamJoiner` — see source for methods

## Testing

```bash
cargo test
```

8 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: other
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates


## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
