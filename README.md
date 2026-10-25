<p align="center"><img src="pinksky.svg" width="128" alt="PinkSky"></p>

<h1 align="center">PinkSky</h1>

<p align="center">Nativní GNOME klient pro Bluesky a Mastodon<br>
<i>A native GNOME client for Bluesky and Mastodon</i></p>

## Funkce

- **Bluesky i Mastodon:** účty obou sítí v jedné aplikaci, přepínání mezi nimi.
  Mastodon s přihlášením k libovolné instanci, časovými osami Domů / Místní /
  Federovaná, seznamy a sledovanými hashtagy.
- **Crossposting:** jeden příspěvek najednou na víc účtů (Bluesky i Mastodon).

- **Feedy:** Sledované, Discover a vlastní připnuté feedy, správa a objevování feedů, tlačítko „Nové příspěvky“.
- **Příspěvky:** vlákna, profily, hledání s trendy, uložené příspěvky (záložky).
- **Psaní:** obrázky s ALT textem, @zmínky, emoji, náhled odkazu, koncepty, naplánované příspěvky, nastavení kdo může odpovídat.
- **Zprávy (DM)** a seskupená **oznámení**, i se zavřeným oknem.
- **Ikona v horní liště** a hledání v přehledu GNOME.
- **Více účtů**, hesla aplikací v GNOME Klíčence.
- **Automatické aktualizace** z GitHubu jedním klikem.
- Světlý i tmavý režim, **čeština a angličtina**.

## Instalace

Stáhněte si poslední vydání v sekci [Releases](../../releases).

**Flatpak – Ubuntu, Debian, Linux Mint, Fedora a další distribuce:**

```bash
flatpak install --user ./pinksky-*.flatpak
```

Potřebné knihovny GNOME si flatpak stáhne sám z Flathubu. Na Ubuntu nejdřív nainstalujte flatpak:
`sudo apt install flatpak` a přidejte Flathub:
`flatpak remote-add --user --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo`.

Balíčky RPM a archiv `.tar.gz` vyžadují **GTK 4.20+** a **libadwaita 1.8+** (Fedora 43+, Ubuntu 25.10+).

**Fedora (RPM, systémová instalace):**

```bash
sudo dnf install ./pinksky-*.x86_64.rpm
```

**Archiv (instalace do domovské složky, bez sudo):**

```bash
tar xzf pinksky-*-x86_64.tar.gz
cd pinksky-*-x86_64
./install.sh
```

Odinstalace: `./install.sh --uninstall`.

## Přihlášení

- **Bluesky:** použijte **heslo aplikace**, ne hlavní heslo k účtu. Vytvoříte ho v aplikaci Bluesky v *Nastavení → Soukromí a zabezpečení → Hesla aplikací*.
- **Mastodon:** zadejte svůj server (např. `mastodon.social`) a přihlaste se v prohlížeči.

## English

PinkSky is a native GNOME client for Bluesky and Mastodon with crossposting between both networks, feeds, threads, direct messages, notifications, drafts, scheduled posts, multiple accounts, GNOME Shell search and automatic updates. Download it from [Releases](../../releases): the **Flatpak** bundle works on Ubuntu, Debian, Mint, Fedora and most other distributions; the RPM and `.tar.gz` archive require GTK 4.20+ and libadwaita 1.8+. Sign in to Bluesky with an **app password**, to Mastodon through your browser.

## Licence / License

Freeware, viz [LICENSE](LICENSE). PinkSky je nezávislý klient a není spojen se společností Bluesky Social, PBC.

© 2026 [Libor Macák](https://libormacak.eu)
