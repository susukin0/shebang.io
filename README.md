🌀 Simplicity

Shebang is built to be fast, intuitive, and efficient — no bloat, no noise.

    Minimal yet powerful desktop: Powered by Openbox for speed and clarity.

    Polymenu: A centralized menu with quick access to tools, including Polymenu > Network > IRC to connect with the Shebang community via Tor.

    Smart hotkeys:

        Super + Vim – Launch your editor

        Super + Escape – Show desktop

        Windows + D – App search

        Windows + X – Shutdown/reboot

        Super + T – Terminal

        Super + W – Mullvad Browser (default browser)

        Ctrl + Escape – Easter egg 🐣

    Welcome script at startup: Auto-configures directories, packages, and memory-based runtime environments every boot. Simple, clean, and repeatable. 

    Flatpak support: Easily install and sandbox modern applications with Flatpak — wide software availability with better isolation.
    
    You can adjust some featuress like brightness, bluetooth, wifi connection, notification, airplane mode, tor router (click on lock icon) on polybar.
    For example, at top left corner (eye icon), you can mute your mic and webcam.
    
    Shebang has newsboat, (you can configure it) that notifies you some basic global news once in a while.

    You may want to take a look at .config/openbox/autostart for some personal customizations.


🔐 Security

Security is deeply integrated, not just layered on top.

    LUKS Disk Encryption (recommended): Protect your full disk with strong encryption, keeping your data unreadable without your passphrase.

    MAC address spoofing: A new MAC is generated with every connection, preventing device tracking.

    RAM-based folders: /home, .config and /tmp operate entirely in RAM — no traces are left behind on disk after reboot.

    System hardening: Secure CPU, GRUB, and SYSCTL configurations are applied automatically for improved protection and performance.

    Privacy toggle: Instant control over mic and camera via the corner icon — hardware-level awareness, no guesswork.

    Ephemeral sessions: Since most of the system lives in RAM, every boot is a fresh, clean environment.

🕵️ Privacy

Privacy isn't optional in Shebang — it's the standard.

    Tor-enabled by default:

        xterm (mksh)is routed through Tor out of the box.

        IRC chat connects via Tor, providing secure, anonymous access to the Shebang community.

    Mullvad Browser (default): A privacy-first browser that’s hardened and DNS-isolated. Paired with Flatpak, it ensures your browsing stays private and contained.

    Encrypted communication: Mullvad’s DNS system and Tor routing protect you from leaks and surveillance.

    Hardened /etc/hosts file: Blocks countless intrusive web services at the system level. Less noise, fewer trackers, better privacy.

    No telemetry, ever: Shebang ships with zero data collection or background tracking.
