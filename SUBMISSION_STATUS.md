# BA3073 verified source — 2330036177

Updated 2026-11-02T22:37:06+08:00. Task 3 is incomplete.

Local Docker, revised essay prompt, 12 frontend/117 backend tests, local amd64 build, private ACR push, matching digest-pinned ECS pull, direct-IP UI and one real cloud model-generated report are verified. Clean dependency build failed on Docker Hub; Dockerfile.cached reused a matching runtime.

Latest Task 3 attempt: official cloudflared 2026.10.7 checksum-verified and installed; Nginx configured at 127.0.0.1:18080; both services active. Temporary endpoint: https://style-mixing-van-advancement.trycloudflare.com/ui/
Anonymous request: HTTP 302 to email authentication, TLS certificate verification result 0. The student completed the email PIN, but JavaScript/CSS redirected to authentication and failed CORS checks. Full application UI and persistent authorized admission are NOT verified. Backend direct-IP access remains restricted to the authorized /32; it has not been closed because the replacement path is unverified.

No student-controlled DNS A record to ECS or Certbot certificate on ECS. No domain purchased. Temporary provider hostnames are not equivalent to the specified architecture and may stop/change. Do not describe this as a completed Task 3. See docs/deployment/QUICK_TUNNEL.md.

The complete revised source is the ZIP at this repository root. The expanded tree retains the teaching baseline plus the separately committed essay prompt. Secrets, data, workspace, generated artifacts and dependencies are excluded. Public repository: https://github.com/nnnancy-oi/BA3073_AI_Learning_Assistant_2330036177
