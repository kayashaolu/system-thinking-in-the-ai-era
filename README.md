# Systems Thinking in the AI Era - Code Repository

This repository contains the Python code for the **Systems Thinking in the AI Era** course series. It includes the 7 universal building blocks, 3 external entities, and interactive discovery labs.

## Repository Structure

```
systems-thinking-code/
├── building_blocks/
│   ├── building_blocks.py    # The 7 universal building blocks
│   └── external_entities.py  # The 3 external entities
│
├── labs/
│   └── course1/
│       ├── lab1_queue_worker.py   # Queue + Worker Discovery Lab
│       └── lab2_time_worker.py    # Time + Worker Discovery Lab
│
└── challenges/
    └── course1/
        ├── part1-mvp-foundation.md    # ChefConnect MVP Design
        ├── part2-viral-growth.md      # Scaling & Growth Challenge
        └── part3-live-streaming.md    # Live Streaming Extension
```

## The 7 Building Blocks

| Type | Block | Description |
|------|-------|-------------|
| Task | **Service** | Request/response processing |
| Task | **Worker** | Background processing |
| Storage | **Queue** | Message passing and task management |
| Storage | **Key-Value Store** | Caching and fast lookups |
| Storage | **File Store** | Media and large file storage |
| Storage | **Relational Database** | Structured data with relationships |
| Storage | **Vector Database** | AI embeddings and similarity search |

## The 3 External Entities

| Entity | Description |
|--------|-------------|
| **User** | Human interactions with the system |
| **External Service** | Third-party APIs and integrations |
| **Time** | Scheduled triggers and time-based events |

## Running the Labs

### Prerequisites
- Python 3.8+
- No external dependencies required (all labs are self-contained)

### Lab 1: Queue + Worker Discovery
```bash
python labs/course1/lab1_queue_worker.py
```

### Lab 2: Time + Worker Discovery
```bash
python labs/course1/lab2_time_worker.py
```

## Design Challenge Templates

The `challenges/` folder contains Technical Design Document templates for the system design challenges:

| Part | Challenge | Description |
|------|-----------|-------------|
| 1 | **MVP Foundation** | Design ChefConnect's initial architecture with 5 core requirements |
| 2 | **Viral Growth** | Scale the system to handle explosive user growth |
| 3 | **Live Streaming** | Add real-time cooking session capabilities |

### How to Use
1. Download the template for the challenge part you're working on
2. Fill in your architecture decisions using building block terminology
3. Submit via the course website for AI-powered feedback

## Course Information

This code accompanies the [Systems Thinking in the AI Era](https://systemthinkinglab.ai) course series:

- **Course I:** The Seven Building Blocks (Foundation)
- **Course II:** Content Systems (Coming 2026)
- **Course III:** Real-Time Systems (Coming 2026)
- **Course IV:** Business Integration Systems (Coming 2026)

## License

This code is provided for educational purposes as part of the Systems Thinking in the AI Era course series.

## Author

Kay Ashaolu - [UC Berkeley School of Information](https://www.ischool.berkeley.edu/people/kay-ashaolu)
