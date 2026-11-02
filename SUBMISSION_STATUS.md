# BA3073 verified student source - 2330036177

Updated 2 November 2026. Task 3 remains incomplete; do not describe this as a fully complete assignment.

The complete current source is supplied as BA3073_2330036177_source.zip at the repository root. Use that snapshot to reproduce the verified deployment. The expanded repository tree retains the imported teaching baseline, with the revised essay prompt also committed as an individual file.

Verified work:

- Local Docker project healthy, localhost-only binding, actual Safari interface and local-ui-check.txt PASS. Current local screenshot retained outside the source archive.
- Revised BA3073 essay instructions in backend/pipelines/essay_html.py; 12 frontend and 117 backend tests passed. Clean dependency download failed at Docker Hub authorization; successful source-overlay builds reused existing matching-architecture runtime images via Dockerfile.cached.
- Local amd64 image pushed to private Hangzhou ACR and pulled on ECS at the same digest: sha256:a93dc14f240116d4a95f6577689cf62d4560fbdd6147b05273f2a45324e4f266.
- ECS container 92a08e22a1cf remains healthy after recreation. Existing mounts, settings and student account preserved; private consistent backup exists, restore untested.
- Actual Chrome login interface verified at http://120.26.28.223:14242/ui/ after updating the source IPv4 /32 when the client network changed, and adding a one-host system proxy exception with explicit consent. No public all-source 14242 rule was added.
- One real cloud service-core run generated HTML and PDF using qwen3.6-flash; original manifest/output retained outside source. Report was subsequently fact-checked and actual screenshots inserted.
- Source repository made public after the user's explicit approval and GitHub reauthentication. Secrets, runtime data, generated artifacts and dependency folders excluded from the source archive.

Still missing:

- Authorized domain/subdomain, DNS and applicable mainland ICP filing/access requirements.
- Actual Nginx, trusted HTTPS, independent proxy access gate, admission/rejection verification and domain/address-bar evidence.
- Final report after Task 3. The current report is an interim draft.

The ECS-origin public-IP self-check still times out; it remains FAIL in the preserved logs. Loopback health, authorized external HTTP and actual Chrome UI rendering are separate successful observations. No root cause is asserted for the self-request failure.

Reports, browser captures, passwords, model settings, data/ and workspace/ are deliberately outside this source snapshot.
