# BuildCored-Orcas-Day30
Expert: OrcaOS — BUILDCORED ORCAS Day 30

What it does. OrcaOS is a unified control center that combines gesture tracking, local AI chat and live sensor monitoring into a single terminal interface. It acts like a Personal OS that can see, listen to and reason about hardware all at the same time.

Hardware concept. The project uses an Realtime operating system architecture where different tasks like camera tracking and sensor reading, run as background workers that share information through a central state. This mimics how actual industrial firmware manages multiple hardware components simultaneously.

Screen recording. https://drive.google.com/file/d/1NZLsukPOi-nmQuWTWSt8bO4oxI4xQRKN/view?usp=sharing

What I would do differently. I would optimize the gesture detection to handle lower lighting and different camera angles more reliably. I'd also try to integrate a physical hardware component like an Arduino to see how this TUI shell could control external LEDs or motors in the real world.

Run it. python day30_starter.py
