✅ BEGINNER (What you already learned)

These are the essential building blocks:

Key–value pairs

Indentation rules (spaces only)

Lists (-)

Nested maps and nested lists

Multi-line text (| and >)

Anchors & aliases (& and *)

Basic data types (string/number/bool/null/date)

Comments (#)

These give you enough skill to read and write most YAML.

🔶 INTERMEDIATE (Next things to learn — optional but useful)

These are the next topics you can learn:

YAML directives (%YAML)

Document separators (--- and ...)

Flow style (inline YAML)
Example:

fruits: [apple, banana, mango]
person: {name: John, age: 25}


Tagging types (!!str, !!int, etc.)

Custom data types

Merge keys (<<:)

YAML validation (linting)

🔥 ADVANCED (Used a lot in DevOps tools)

Schema-based YAML (Kubernetes, Ansible, Docker)

Environment variable substitution

YAML templating (Helm, Jinja2, Ansible variables)

Anchors in complex structures

Multi-document YAML files (common in Kubernetes)
Example:

---
apiVersion: v1
kind: Pod
---
apiVersion: v1
kind: Service


YAML security (avoiding unsafe parsing)