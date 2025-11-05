# VTS - Vacation Tracking System

## Overview

The VTS (Vacation Tracking System) is a comprehensive workflow management system designed to handle employee vacation requests and manager approval processes. This system streamlines the request submission and approval workflow with clear process flows and role-based interactions.

## Project Structure

```
VTS/
├── #01 Sequence Employee submits a new request.svg
├── #02 Sequence Manager approval flow.svg
├── VTS_Flow_chart.svg
├── Untitled Diagram.drawio
├── VTS .pdf
└── README.md
```

## Files Description

### Diagrams and Documentation

| File | Type | Description |
|------|------|-------------|
| `#01 Sequence Employee submits a new request.svg` | Sequence Diagram | Illustrates the complete workflow when an employee submits a new vacation request |
| `#02 Sequence Manager approval flow.svg` | Sequence Diagram | Shows the manager's approval process and decision flow |
| `VTS_Flow_chart.svg` | Flow Chart | Overall system flow chart depicting the entire VTS process |
| `Untitled Diagram.drawio` | Draw.io Source | Editable diagram source file for modifications |
| `VTS .pdf` | PDF Document | Complete documentation and specification document |

## System Workflows

### 1. Employee Request Submission Flow

The employee request submission process is documented in the sequence diagram below:

![Employee Request Submission](./#01%20Sequence%20Employee%20submits%20a%20new%20request.svg)

**Key Steps:**
- Employee initiates a vacation request
- System validates the request
- Request is submitted to the approval queue
- Employee receives confirmation

### 2. Manager Approval Flow

The manager approval process is illustrated in this sequence diagram:

![Manager Approval Flow](./#02%20Sequence%20Manager%20approval%20flow.svg)

**Key Steps:**
- Manager receives notification of pending requests
- Manager reviews request details
- Manager makes approval/rejection decision
- System updates request status
- Employee receives notification of decision

### 3. Complete System Flow Chart

The overall system architecture and process flow:

![VTS Flow Chart](./VTS_Flow_chart.svg)

## Features

- **Employee Self-Service**: Employees can submit vacation requests independently
- **Manager Dashboard**: Centralized view for managers to review and process requests
- **Automated Notifications**: Real-time updates for both employees and managers
- **Request Tracking**: Complete audit trail of all requests and decisions
- **Workflow Automation**: Streamlined approval process with defined stages

## Workflow States

1. **Draft** - Request being prepared by employee
2. **Submitted** - Request sent for approval
3. **Pending Review** - Awaiting manager action
4. **Approved** - Request approved by manager
5. **Rejected** - Request declined by manager
6. **Cancelled** - Request withdrawn by employee

## Roles and Permissions

### Employee
- Submit new vacation requests
- View own request history
- Edit draft requests
- Cancel submitted requests (before approval)
- Receive notifications on request status

### Manager
- View all team member requests
- Approve or reject pending requests
- Add comments/notes to requests
- View team vacation calendar
- Receive notifications for new requests

## Getting Started

### Prerequisites
- Access to the VTS system
- Valid employee or manager credentials
- Network connectivity to the application server

### For Employees
1. Log in to the VTS system
2. Navigate to "New Request"
3. Fill in the vacation request form
4. Submit for approval
5. Monitor request status in your dashboard

### For Managers
1. Log in to the VTS system
2. Access the "Pending Approvals" section
3. Review request details
4. Approve or reject with optional comments
5. Track team vacation schedule

## Documentation

For detailed system documentation, please refer to:
- [Complete VTS Documentation](./VTS%20.pdf)

## Diagrams

All system diagrams are available in SVG format for high-quality viewing:
- [Employee Request Flow](./#01%20Sequence%20Employee%20submits%20a%20new%20request.svg)
- [Manager Approval Flow](./#02%20Sequence%20Manager%20approval%20flow.svg)
- [System Flow Chart](./VTS_Flow_chart.svg)

## Editing Diagrams

The source diagrams can be edited using Draw.io:
1. Open [Draw.io](https://app.diagrams.net/)
2. Import the `Untitled Diagram.drawio` file
3. Make your modifications
4. Export as SVG or PNG as needed

## Support and Maintenance

For system support or to report issues, please contact your system administrator.

## Version History

- **v1.0** - Initial system design and documentation

## License

Copyright © 2024. All rights reserved.

---

**Last Updated**: November 2024
