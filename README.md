Grab an api key from [Openstatus.dev](https://www.openstatus.dev)

open terminal run the following commands:

```
git clone https://github.com/sudo-self/domain-status.git
cd domain-status
touch .dev.vars
nano .dev.vars 
```
add the api key from openstatus API_KEY=

[ctrl] + o 
[ctrl] + x

deploy with cloudflare pages

```
pnpm install -g wrangler
pnpm build
npx wrangler pages deploy dist
```

<img width="1440" alt="Screenshot 2024-01-28 at 2 59 22 PM" src="https://github.com/sudo-self/domain-status/assets/119916323/8e2416c7-f396-4702-bd60-cdeb8b890f62">
<img width="1104" alt="Screenshot 2024-01-28 at 5 00 48 PM" src="https://github.com/sudo-self/domain-status/assets/119916323/c6b0d434-5267-44cd-af60-af6b0feca920">



