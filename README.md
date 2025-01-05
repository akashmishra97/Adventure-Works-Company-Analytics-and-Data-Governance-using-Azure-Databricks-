# Adventure-Works-Company-Analytics-and-Data-Governance-using-Azure-Databricks-

## Overview

This project demonstrates the implementation of a secure and scalable Data Access Management System for the Adventure Works Company using **Azure Databricks** and **Unity Catalog**. It showcases an enterprise-level architecture for data governance, enabling role-based access control (RBAC), row-level security (RLS), and actionable insights through dashboards.

---

## Features

- **Multi-layered Data Architecture**:
  - **Bronze Layer**: Raw, untransformed data.
  - **Silver Layer**: Cleaned and standardized data for analytical use.
  - **Gold Layer**: Aggregated, business-ready data for dashboards and reporting.

- **Role-Based Access Control (RBAC)**:
  - Implemented using Unity Catalog to ensure fine-grained access to data assets.

- **Row-Level Security (RLS)**:
  - Applied to ensure region-specific and role-specific data access.

- **Dashboards**:
  - Role-specific insights and analytics for different users.

- **Data Governance**:
  - Metadata management, data lineage, and policy enforcement with Unity Catalog.

---

## Project Objectives

1. Implement a secure data platform using **Microsoft Azure** and **Databricks**.
2. Establish a multi-layered data architecture (Bronze, Silver, Gold).
3. Apply **RBAC** and **RLS** for enhanced data security.
4. Develop role-based dashboards for actionable insights.
5. Enable centralized metadata management and data lineage tracking.

---

## Key Technologies

- **Azure Databricks**
- **Azure Data Lake Storage**
- **Unity Catalog**
- **SCIM Integration** for user provisioning
- **Azure Entra ID** for identity management

---

## Architecture

1. **Azure Setup**:
   - User creation in Azure Entra ID.
   - Resource provisioning for Databricks and Azure Data Lake Storage.

2. **Data Layers**:
   - Raw data from **Azure Data Lake Storage (ADLS)** is transformed and stored in a multi-layered architecture.

3. **Role Definitions**:
   - Data Engineers, Analysts, Business Analysts, Sales, and Marketing users with distinct access levels.

4. **Dashboards**:
   - Secure and role-specific visualization for key metrics.

---

## Lessons Learned

- Designing role-based systems enhances data security and democratization.
- SCIM integration automates user provisioning and role synchronization.
- Unity Catalog streamlines metadata management and improves governance.

---

## Resources

- [Azure Databricks Getting Started Guide](https://docs.microsoft.com/azure/databricks/)
- [Unity Catalog Documentation](https://docs.databricks.com/unity-catalog/index.html)
- [SCIM Integration Guide](https://learn.microsoft.com/azure/active-directory/scim/)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or support, please reach out to:

- **Name**: Akash Mishra
- **Email**: akash.mishra8697@gmail.com


