# Job Tracker

CLI tool to track job applications, their status, and provide visibility into your job search pipeline.

## Features

- Add job applications
- List and filter applications by status
- Update application status
- View statistics

## Installation

```bash
git clone git@github.com:Freddster16/job-tracker.git
cd job-tracker
```

## Usage

### Add an application
```bash
python main.py add "Company" "Role" "status" "date"
```

### List all applications
```bash
python main.py list
```

### Filter by status
```bash
python main.py list --status applied
```

### Update status
```bash
python main.py update <id> "new_status"
```

### Show statistics
```bash
python main.py stats
```

## Development

This project is built in phases:
- **v1**: CLI + JSON storage (current)
- **v2**: SQLite database
- **v3**: REST API
- **v4**: Web frontend
- **v5**: AI features

## License

MIT
