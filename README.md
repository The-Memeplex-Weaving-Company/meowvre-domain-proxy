# meowvre-domain-proxy

Fronts `meowvre.catbal.io` (registered under the devcatbal Vercel
account) and transparently proxies every request to the actual
Meowvre museum, which is hosted under a different Vercel account
(meowvre, Memeplex team) at meowvre.vercel.app.

No build step, no app code — `vercel.json`'s rewrite rule does all
the work at Vercel's edge.
