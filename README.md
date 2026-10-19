<p align="center"><img src="pinksky.svg" width="128" alt="PinkSky"></p>

<h1 align="center">PinkSky</h1>

<p align="center">Nativní GNOME klient pro sociální síť Bluesky<br>
<i>A native GNOME client for the Bluesky social network</i></p>

## Funkce

- **Feedy:** Sledované, Discover a vlastní připnuté feedy, správa a objevování feedů, tlačítko „Nové příspěvky“.
- **Příspěvky:** vlákna, profily, hledání s trendy, uložené příspěvky (záložky).
- **Psaní:** obrázky s ALT textem, @zmínky, emoji, náhled odkazu, koncepty, naplánované příspěvky, nastavení kdo může odpovídat.
- **Zprávy (DM)** a seskupená **oznámení**, i se zavřeným oknem.
- **Ikona v horní liště** a hledání v přehledu GNOME.
- **Více účtů**, hesla aplikací v GNOME Klíčence.
- Světlý i tmavý režim, **čeština a angličtina**.

## Požadavky

Linux x86_64 s **GTK 4.20+** a **libadwaita 1.8+**, například Fedora 44.

## Instalace

Stáhněte si poslední vydání v sekci [Releases](../../releases).

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

Pro přihlášení použijte **heslo aplikace**, ne hlavní heslo k účtu. Vytvoříte ho v aplikaci Bluesky v *Nastavení → Soukromí a zabezpečení → Hesla aplikací*.

## English

PinkSky is a native GNOME client for Bluesky with feeds, threads, direct messages, notifications, drafts, scheduled posts, multiple accounts and GNOME Shell search. It requires GTK 4.20+ and libadwaita 1.8+ (e.g. Fedora 44). Download the RPM or the `.tar.gz` archive from [Releases](../../releases) and sign in with an **app password**.

## Licence / License

Freeware, viz [LICENSE](LICENSE). PinkSky je nezávislý klient a není spojen se společností Bluesky Social, PBC.

© 2026 [Libor Macák](https://libormacak.eu)
