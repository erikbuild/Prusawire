# Prusawire 2025.B1

![Render](Assets/render.png)

An unofficial Prusa MK3 and MK4 total conversion mod, from Positron's April Fools of 2025.

## Current Release

Beta 1 (2025.B1) was released on 2025-08-21.  There have been [updates and improvements since then](CHANGELOG.md).  Be sure to grab the latest STLs and documentation from the GitHub Repository.

Release 1 (2026.R1) is coming SOON(tm)!

Link to Beta 1 CAD Viewer: [Link](https://positron3d.autodesk360.com/g/shares/SH30dd5QT870c25f12fc28f5f9169dbff2f2)

Link to instructions for gantry de-racking & installing XZ and Y belts: [Link](https://prusawire.positron3d.com/hardware/)

## About

> Nomad of Positron3D came up with this idea shortly after completing their Switchwire build. The idea started as a quick design exercise, to try and convert a Prusa MK4S frame into a Switchwire, using everything left over from a CORE One Upgrade.
>
> As the first iteration wrapped up, I took interest in the project, and decided to take this April Fools joke one step further and build it into a reliable machine.
>
> After months of hard work, please enjoy the build ❤
> 
> -@ellafoxo

## Who This Printer is For

Pick one of the following:

- You have an old MK3, MK3S, or MK3S+, and you want to teach an old dog new tricks and are on a budget
- You upgraded from MK4S to a Core ONE, and have a leftover frame. You are okay spending money on building a new printer with that hardware.

Additionally, the following says this printer is for you: 

- You want to take your first steps into RepRap beyond Prusa, and Voron is an exciting route.
- You are comfortable working from a CAD file as your build guide
- You respect the Frankenstein-y nature of this April Fools joke printer

## Want to Support the Project?

First of all, thank you! Development costs have been mostly self-funded, with filament sponsored by Levendigs, and LDO Motors for providing the funds for the Prusa MK4 frame.

- Support Positron3D to fund future endeavors: 
   - [Donate to Positron3D](https://www.paypal.com/donate/?hosted_button_id=YGPRVTSHN4FQG)
   - [Positron3D Merch](https://nomadsgalaxy-shop.fourthwall.com/)

## Build Volume

X: 250mm
Y: 210mm
Z: 185mm

## Bill of Materials

[Prusawire 2025.B1 Bill of Materials](BOM/BOM_2025-B1.md)

## Technical Support

Prusawire, technically, does not count as a Voron Switchwire. We ask you kindly not to nag the Voron Design team for technical support.

Instead, please [join the Positron3D Discord](https://discord.gg/positron) for support with your build, and maybe share your progress over there too.

## Serial Numbers

We are accepting serials over on the [Positron 3D Discord](https://discord.gg/positron). Please submit your request to the #prusawire-serial-request channel over there. 

## Upgrading the Einsy Rambo to Klipper - Read this

Installing Klipper on the Einsy Rambo board is possible, with extra steps. Follow the guide [published by the awesome folks at MyRigs3D](https://myrigs3d.com/blogs/infos/revive-your-prusa-mk3s-with-klipper-1-5-flash-bootloader)! We recommend Method 2.

**Note:** Some users have reported problems using `avrdude` with the latest Raspberry Pi OS version (bookworm). If you experience error messages from avrdude complaining about gpio ports being busy, please try using the bullseye version of Raspberry Pi OS instead, available as "Raspberry Pi OS (Legacy)" in Raspberry Pi Imager.

## Klipper Configuration Files

The most up–to–date Klipper configuration files for setting up or updating the Prusawire are in our [config repository](https://github.com/Positron3D/prusawire-klipper-config).

## Credits 

Many thanks to all the awesome people and companies that have made this possible. Notably:

Most importantly:
- Ella Fox, _the architect of Beta 1_ - who took Prusawire from a joke to a beautiful and powerful machine. [Buy Ella a Ko-Fi](https://ko-fi.com/ellafoxo)

And also:
- Prusa Research - Cheers, Josef and the team for the MK3/4 platform on which this was built upon!
- Voron Design - Switchwire

- Positron 3D Team - Too many to name, you know who you are <3
- Early development team:
   - Nomad's Galaxy
   - Koosh
   - Birb
- Jason @ LDO Motors - Part sponsorship
- Levendigs - Part sponsorship 
- Early access testers:-
   - Killa_Prints
   - LinksLab
   - Safe
   - Silicon
   - TheNexusAvenger
   - torsten
- Contributors since Beta 1
   - einarjh
   - erikbuild

## Extra Credits for Existing Printed Parts

See the collection for the most up to date! To name them:

- Printable M3 T-Nuts for 3030 Extrusion, by Kapplion
- Stealthburner umbilical strain relief, by nagelwerkstatt

## Team

Prusawire is currently maintained by the Positron 3D Team.

- Design Lead: @Safe-ty
- Documentation Lead: @erikbuild
- Software Lead: @TheNexusAvenger
