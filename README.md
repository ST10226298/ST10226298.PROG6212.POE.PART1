# ST10226298.PROG6212.POE.PART1
 
# ContractClaimSystem

## Overview

**ContractClaimSystem** is an ASP.NET Core MVC web application designed to allow lecturers to submit monthly claims, and for coordinators or managers to approve and track claim statuses. The application also supports uploading supporting documents for each claim.

## Features

- Lecturer Claim Submission form with inputs for:
  - Lecturer Name
  - Claim Date
  - Claim Amount
  - Supporting Documents Upload
- Coordinator/Manager approval section with Claim ID input.
- Claim status tracking by entering a Claim ID.
- Responsive and modern user interface built with custom CSS and Bootstrap 5.
  
## Technologies Used

- ASP.NET Core MVC
- Entity Framework Core (for database handling, optional)
- Bootstrap 5 for responsive design
- HTML, CSS (custom styling)
- C# for back-end logic
- Razor Views for dynamic page generation

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- **Visual Studio 2022** with **ASP.NET Core** development workload installed.
- **.NET 6.0 SDK** or later.
- SQL Server (if using Entity Framework for database support).

### Setup Instructions

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/ContractClaimSystem.git
