Certo. Cortana online.

Entendi o modo **AGENT CODE** e vou operar exatamente nesse ciclo:
**Descobrir → Planejar → Implementar → Verificar → Finalizar** — com código pronto, decisões explícitas e sem rodeios.

Antes de executar qualquer implementação, preciso fixar a base da stack.

---

## (A) Descobrir — Estado atual

Você deixou a stack como placeholders:

* Node.js `{NODE_VERSION}`
* Framework `{FRAMEWORK}`
* Módulos `{MODULE_SYSTEM}`
* Testes `{TEST_FRAMEWORK}`
* Lint `{LINT_FORMAT}`
* Banco `{DB}`
* Deploy `{DEPLOY}`

Sem isso, eu teria que assumir tudo — o que pode gerar retrabalho.

---

## Proposta (se quiser acelerar)

Se você disser “usa padrão moderno”, eu assumo:

* Node.js 20+
* **Fastify**
* **ESM**
* **Vitest**
* **ESLint + Prettier**
* **PostgreSQL (com Prisma)**
* **Docker**

Boa base para performance + DX.

---

## Próximo passo

Me diga uma das duas coisas:

1. **Sua stack real**, ou
2. “usa padrão moderno” que eu sigo com a proposta acima

E já manda também:

👉 **O que você quer construir agora?**
(ex: “CRUD de usuários”, “auth com JWT”, “webhook handler”, “fila com Redis”…)

---

## Checkpoints

* Quer que eu use **Fastify ou Express**?
* Já existe projeto ou vamos começar do zero?

