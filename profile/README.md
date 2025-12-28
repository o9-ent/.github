# o9-ent: o9 Enterprise Organization

Welcome to **o9-ent** — a GitHub organization that serves as the enterprise-level representation for the o9 GitHub Enterprise.

## What is o9-ent?

**o9-ent** is an organizational structure that maps the o9 GitHub Enterprise onto itself as a GitHub organization. It operates one level below the global scope (o9-glo), providing a focused view of the o9 enterprise structure.

## The Microcosm Mapping Pattern

We use the microcosm mapping pattern adapted to the enterprise level:

- **The o9 Enterprise** → This GitHub Organization (o9-ent)
- **Organizations** (within o9 enterprise) → Repositories (in o9-ent)
- **Repositories** (within those orgs) → Folders (in those repositories)

### Hierarchical Structure
```
o9-glo (global scope)
└── o9 enterprise (repository in o9-glo)
    └── o9-ent organization (folder in o9 repo)
        └── org-repo (this maps to repositories in o9-ent)
            └── repo-folders/ (folders representing individual repos)
```

### Example Structure
```
o9-ent/e9-o9 (repository representing e9-o9 organization)
├── repo1/ (folder = repository)
│   └── metadata.md
├── repo2/ (folder = repository)
│   └── metadata.md
└── README.md (organization overview)
```

## Understanding the Hierarchy

**o9-ent** fits into a three-level hierarchy:

1. **o9-glo** (Global Scope) - Maps enterprises to repositories
   - Enterprises → Repositories
   - Organizations → Folders
   - Repositories → Files

2. **o9-ent** (Enterprise Level) - Maps o9 organizations to repositories
   - o9 Enterprise → This Organization
   - Organizations → Repositories
   - Repositories → Folders

3. **Individual Organization Repositories** - Contains folders for each repository

## Our Organizations

**o9-ent** maps the organizations within the o9 GitHub Enterprise, including:

- **e9-o9**: Core o9 engineering organization
- **o9-glo**: Global scope organization (self-referential)
- **o9nn**: Neural network and AI organization
- And other o9 enterprise organizations

Each organization is represented as a repository within o9-ent, containing folders for the organization's individual repositories.

## The .github Repository

This repository ([o9-ent/.github](https://github.com/o9-ent/.github)) is a special GitHub repository that:
- Defines the public organization profile
- Provides documentation about the o9-ent structure
- Serves as the entry point for understanding our enterprise-level mapping

## Why This Matters

This structure provides several benefits:

1. **Enterprise Focus**: Dedicated view of the o9 enterprise without global scope clutter
2. **Navigability**: Easily browse o9 organizations and their repositories
3. **Documentation**: Each level (organization, repository) is documented with metadata
4. **Scalability**: New organizations and repositories can be added seamlessly
5. **Hierarchical Clarity**: Clear positioning within the global microcosm structure

## Relationship with o9-glo

**o9-ent** is one level lower than **o9-glo**:

- **o9-glo** operates at the global scope, mapping multiple enterprises
- **o9-ent** operates at the enterprise level, mapping organizations within the o9 enterprise
- o9-ent appears as a folder within the o9 repository in o9-glo
- o9-glo appears as a repository within o9-ent (since o9-glo is an organization in the o9 enterprise)

This creates an interesting relationship where both organizations reference each other at different hierarchical levels.

## Exploring the Microcosm

To explore the o9 enterprise microcosm:

1. Browse the repositories in this organization — each represents an o9 organization
2. Within each repository, explore the folders — each represents a repository within that organization
3. Review the README files for metadata and documentation about each level

For the global view, visit [o9-glo](https://github.com/o9-glo) to see how o9-ent fits into the larger enterprise landscape.

---

*Part of the o9 enterprise microcosm representation*  
*Microcosm mappings are auto-generated and regularly updated*
