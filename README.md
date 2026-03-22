# Dockerfile Examples

A curated collection of Dockerfile examples demonstrating best practices for container image creation. Each example focuses on a specific Docker instruction or pattern.

## Repository Structure

This repository organizes Dockerfile snippets by Docker instruction:

- **CMD/** - Examples of CMD instruction variations
- **COPY/** - Patterns for copying files into images
- **EXPOSE/** - Port exposure configurations
- **FROM/** - Base image selection and multi-stage builds
- **LABEL/** - Adding metadata to images
- **RUN/** - Package installation and build steps

## Tech Stack

- **Docker** - Container platform
- **Various base images** - Alpine, Ubuntu, Node.js, Python, etc.

## Usage

Each directory contains standalone Dockerfile examples. To build:

```bash
# Navigate to the example directory
cd CMD

# Build the image
docker build -t example-cmd .

# Run the container
docker run --rm example-cmd
```

## Best Practices Demonstrated

- Use of official base images
- Multi-stage builds for smaller images
- Proper layer ordering for build cache efficiency
- Non-root user where appropriate
- Minimal package installation
- Clear labeling and documentation

## Contributing

Feel free to add more examples following the existing directory structure.

## License

MIT