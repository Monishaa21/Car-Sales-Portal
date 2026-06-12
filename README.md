### Car Sales Portal

Car Sales Portal is an ERPNext-based vehicle management system designed to manage car inventory, brands, variants, pricing, and warehouse operations. The system allows users to organize vehicle details, maintain stock records, manage different car variants based on color and vehicle type, and track selling prices efficiently. It helps streamline the vehicle sales process by providing centralized management of car-related information, ensuring accurate inventory control and pricing management.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch version-16
bench install-app car_sales_portal
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/car_sales_portal
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
