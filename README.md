# azure-rbac-managementgroups-lab
his lab demonstrates how to implement **Role-Based Access Control (RBAC)** in Azure and apply **Management Groups** for structured access control in enterprise environments.


# 🔐 Azure Role-Based Access Control (RBAC) & Management Groups Lab

This lab demonstrates how to implement **Role-Based Access Control (RBAC)** in Azure and apply **Management Groups** for structured access control in enterprise environments.

---

## 🌐 Key Concepts

### Role-Based Access Control (RBAC)
RBAC is a way to assign access **based on a user's role** in the business. It ensures the **principle of least privilege** is applied, which enhances security and control over resources.

- **Azure Roles** vs **Microsoft 365 Roles**: Both are role-based, but scoped to different services.
- **Role Definitions**: These are the actual permissions tied to a role.
- **Role Assignments**: The link between a user, a role definition, and a scope (e.g., subscription, resource group, or resource).

✅ Rights are assigned to **roles**, not directly to users.  
✅ Roles are then assigned to users or groups — ensuring centralized, trackable access control.

---

### Management Groups

Management Groups are used to organize and apply **governance policies** across multiple subscriptions.

- Allow grouping of Azure subscriptions into hierarchies.
- Policies and role assignments applied at a **management group level** cascade down to all included subscriptions.
- Useful in large organizations for centralized control.

---

## 🧪 Labs Include

1. Creating custom and built-in **Azure roles**
2. Assigning roles at different scopes: **Resource**, **Resource Group**, and **Subscription**
3. Building and visualizing **Management Group hierarchy**
4. Testing RBAC permissions across users with different roles
5. Reviewing **effective permissions** using Azure Portal and CLI

---

## 📸 Screenshots
azure-rbac-managementgroups-lab/
│
├── README.md
├── screenshots/
│   ├── rbac-role-assignment.png
│   ├── management-group-structure.png
│   ├── role-definition.png
│   └── user-access-summary.png
└── rbac-role-setup.ps1       # (optional if you include any automation)


## 📘 What You’ll Learn

- How to **control access at scale** using RBAC
- The importance of **role separation** in enterprise Azure environments
- How to use **Management Groups** to structure subscriptions and policies
- How **auditability and governance** is improved with RBAC

---

## 💡 Motivation

🔐 *Security starts with structured access.*  
Organizing access using roles makes cloud environments easier to manage, secure, and audit — especially when tied with Management Groups for consistent enforcement across large setups.


