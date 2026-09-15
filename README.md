# integraci-config-source-e2e

Disposable end-to-end fixture for IntegraCI's "deploy from a customer-owned chart
and values in Git" capability (ADR-0053). It holds ONLY per-stage Helm values for
the public `app-template` chart (oci://ghcr.io/bjw-s-labs/helm, 5.1.0). No
credentials, no customer data. Safe to delete after the E2E run (created 2026-09-15).
