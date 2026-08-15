# Interactive Professional Portfolio & Cyber Security CV

An interactive, custom-built web application designed as an expanded, dynamic CV. This portal showcases professional competencies, real-world project deployments, cyber security architecture, and direct integration with **AcmeOS**.

---

## Portfolio Overview & Features

* **Interactive CV & Capability Matrix:** Detailed breakdown of practical skills across DevSecOps, infrastructure engineering, security operations, and software development.
* **Integrated AcmeOS Experience:** Features direct access to **AcmeOS**—a interactive web project—along with a downloadable, step-by-step PDF manual guiding users through system navigation and functionality.
* **Client & Recruiter Contact Form:** Built-in contact form allowing recruiters, hiring managers, and prospective clients to submit inquiries directly.
* **Custom Codebase:** Authored entirely from scratch in semantic HTML5/CSS3 using Visual Studio Code.

---

## Infrastructure & Edge Architecture

Like all core services under the **NTcyber** domain, this portfolio is deployed on self-managed infrastructure using enterprise edge routing:

```text
[ Web Client ] ──► [ Cloudflare Edge ] ──( Secure Tunnel )──► [ Traefik Proxy ] ──► [ Portfolio Container ]
