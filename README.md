### Grab an api key from [Openstatus.dev](https://www.openstatus.dev)

![Screenshot 2024-02-06 at 9 39 40 PM](https://github.com/sudo-self/domain-status/assets/119916323/077e8660-1699-46a9-b233-ac0707c0c2a1)


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

<img width="1277" alt="Screenshot 2024-01-28 at 5 34 55 PM" src="https://github.com/sudo-self/domain-status/assets/119916323/dae17279-8811-427d-8222-b7b7198a1dfa">

```
pnpm install -g wrangler
wrangler pages dev --compatibility-date=2023-12-06 -- astro dev
astro build && wrangler pages deploy ./dist
```
<img width="1440" alt="Screenshot 2024-01-28 at 5 34 31 PM" src="https://github.com/sudo-self/domain-status/assets/119916323/9cd64e39-2413-4f11-b3ce-47feca552981">




