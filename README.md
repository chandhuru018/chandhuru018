# Hi, I'm <Chandhuru R> 

Backend developer from Puducherry, India. I build with Java/Spring Boot and Python, and I like projects that run live, are tested, and come with measured results.

## Featured projects

### [HookRelay](https://github.com/chandhuru018/hookrelay): webhook delivery platform · [Live demo](https://hookrelay-bqsh.onrender.com/swagger-ui.html)
Multi-tenant platform that delivers events to customer URLs with HMAC-signed payloads, retries with backoff, dead-letter replay and SSRF protection. Fixed a real delivery race condition with `SKIP LOCKED`. About 730 events/s at p95 38 ms in local k6 tests, 73 automated tests, CI on GitHub Actions.
`Java 21` `Spring Boot` `PostgreSQL` `Flyway` `Docker` `k6`

### [AI Clinical Documentation Assistant](https://github.com/chandhuru018/clinical-doc-assistant) · [Live demo](https://clinical-doc-assistant.streamlit.app)
Turns doctor–patient conversations (text or audio) into editable SOAP notes with entity extraction and Word export. Runs in the cloud with Groq (Whisper + Llama 3.3 70B), plus an offline mode using my own fine-tuned Llama 3.2 3B (QLoRA on ~9.6k examples, quantized to GGUF).
`Python` `Streamlit` `LLMs` `QLoRA` `Transformers` `spaCy`

### [Smart IoT Printing Kiosk](https://github.com/chandhuru018/smart-printing-backend)
Self-hosted printing kiosk: users upload documents and pay with Razorpay on their phone, then collect the printout with a one-time PIN. A local agent polls for jobs and prints silently; an admin dashboard tracks paper and ink.
`Python` `Flask` `MongoDB Atlas` `Razorpay` `Render`

## Skills
**Languages:** Java, Python, SQL
**Backend:** Spring Boot, Spring Security, JPA, Flask
**Data:** PostgreSQL, MongoDB, Flyway
**Tools:** Docker, GitHub Actions, JUnit, Mockito, k6, Streamlit

## Contact
<www.linkedin.com/in/chandhuru-ramesh> · <chandhurugandhi@gmail.com>
