# Prowler Parser

This tool parses Prowler output files and generates report-friendly summaries. With a user-friendly interface, it’s designed to make analyzing Prowler security assessment results straightforward and accessible.

## Features
- **Easy Parsing**: Quickly converts Prowler output into readable formats.
- **User-Friendly Reports**: Displays parsed data in a clean, report-friendly layout.
- **Containerized**: Run it in a Docker container for quick setup and portability.

## Getting Started

### Prerequisites
- **Docker**: Ensure Docker is installed and running on your machine.

### Installation and Usage

1. **Build the Docker Image**:
   ```bash
   docker build -t pp .
   ```
2. **Run the Tool**:
   ```bash
    docker run -d -v ./app/:/app --rm -p 8501:8501 pp
   ```
3. **Access the Tool**:
   Once running, open a web browser and navigate to http://localhost:8501.
4. **Usage**:
   Upload the prowler json output. Multiple Files are supported
5. **License**:
   Do Whatever the hell you want to do. If you want please do mention my name and website.
