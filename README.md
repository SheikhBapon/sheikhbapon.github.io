# sheikhbapon.com

Sheikh Bapon, Fractional CMO. Static website (HTML only), GitHub Pages ready.

## GitHub e upload + live link (5 min)

1. github.com e login > **New repository** > nam dao `sheikhbapon` > **Public** > Create.
2. Repo page e **"uploading an existing file"** click koro.
3. Ei folder-er **bhitorer shob file + folder** (index.html, assets, downloads, README.md, .nojekyll) drag & drop koro. Folder-ta nije na, bhitorer jinish gula.
4. **Commit changes** chapo.
5. **Settings > Pages** > Source: `Deploy from a branch` > Branch: `main` / `(root)` > **Save**.
6. 1-2 min por link pabe: `https://<tomar-username>.github.io/sheikhbapon/`

## Form first-time activation (ekbar korte hobe)

Form er lead jabe **sheikhbapon782@gmail.com** e (FormSubmit diye, free, kono server lage na).

- Live link theke **nije ekbar form fill koro**.
- Gmail e FormSubmit theke "Confirm your email" mail ashbe (Spam/Promotions o check koro). **Activate** click koro.
- Er por theke protita lead direct inbox e ashbe.
- Email service kono karone fail korle form automatically WhatsApp (01706293285) e lead pathiye dey, tai lead harabe na.

## Pore sheikhbapon.com domain connect korte chaile

1. Settings > Pages > Custom domain e `sheikhbapon.com` dao > Save.
2. Domain er DNS e:
   - `A` record `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record `www` → `<tomar-username>.github.io`
3. DNS update hole **Enforce HTTPS** tick dao.

## Edit kora

- Shob text `index.html` e. Protita line e English `<span class="en">` ar Bangla `<span class="bn">` pashapashi ache.
- Photo change: `assets/img/` e same nam e replace koro.
- Meta Pixel / GA4 add korte chaile `<head>` er bhitore code paste koro. Form submit hole `Lead` event automatically fire hobe.
