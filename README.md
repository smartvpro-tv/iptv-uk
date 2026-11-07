# IPTV in the United Kingdom

A practical, vendor-neutral guide to IPTV for viewers in the UK: what it is, the devices British households use, what is free and legal to stream, the TV licence question, what to check before paying for a subscription, and the questions we hear most often.

Part of the [SmartVPro](https://github.com/smartvpro-tv) open guides. Corrections and additions are welcome through issues and pull requests.

## Contents

- [What IPTV means](#what-iptv-means)
- [Free and legal live TV in the UK](#free-and-legal-live-tv-in-the-uk)
- [The TV licence](#the-tv-licence)
- [Devices UK viewers use](#devices-uk-viewers-use)
- [Broadband speed you need](#broadband-speed-you-need)
- [ISP blocking and VPNs](#isp-blocking-and-vpns)
- [What to check before buying an IPTV subscription](#what-to-check-before-buying-an-iptv-subscription)
- [Common UK channel categories](#common-uk-channel-categories)
- [FAQ](#faq)
- [Local guides by city](#local-guides-by-city)
- [Further reading](#further-reading)

## What IPTV means

IPTV (Internet Protocol Television) is television delivered over broadband rather than aerial, satellite or cable. In the UK it covers:

1. **Broadcaster and pay-TV apps:** BBC iPlayer, ITVX, Channel 4, Sky Stream, NOW, Virgin TV Go, Freely. Licensed and reliable.
2. **Free ad-supported streaming channels:** Pluto TV, Samsung TV Plus, Rakuten TV, Plex. Licensed and free.
3. **Third-party IPTV subscriptions** sold online and delivered as an M3U link, Xtream Codes login or MAG portal, watched in apps such as TiviMate, IPTV Smarters Pro or Smart IPTV. Quality and legality vary widely between sellers.

This guide covers the mechanics that apply to all three, and a checklist for the third category.

## Free and legal live TV in the UK

| Service | What you get | Notes |
|---|---|---|
| [BBC iPlayer](https://www.bbc.co.uk/iplayer) | All BBC channels live and on demand | Requires a TV licence and a free BBC account |
| [ITVX](https://www.itv.com/) | ITV1–4, ITVBe, live and on demand | Free with ads |
| [Channel 4](https://www.channel4.com/) | Channel 4, E4, More4, Film4 live and on demand | Free with ads |
| [Channel 5 / 5](https://www.channel5.com/) | Channel 5 family live and on demand | Free with ads |
| [Freely](https://www.freely.co.uk/) | Live Freeview channels over broadband on supported smart TVs | No aerial needed |
| [Pluto TV](https://pluto.tv/) | 100+ linear channels | Free with ads |
| Freeview (aerial) | 70+ channels in HD | A £15 aerial, no internet |

Freely plus iPlayer, ITVX and Channel 4 gives most UK households every terrestrial channel without a subscription.

## The TV licence

You need a TV licence to watch or record **any** live TV in the UK, whatever the delivery method (aerial, satellite, cable, IPTV, or an app), and to use BBC iPlayer. On-demand content from ITVX, Channel 4 or Netflix does not need a licence. The current fee is published at [tvlicensing.co.uk](https://www.tvlicensing.co.uk/).

## Devices UK viewers use

| Device | Suitability | Notes |
|---|---|---|
| Amazon Fire TV Stick | Best all-round | Most popular UK IPTV device by a wide margin. Sideloads any app. |
| Android TV / Google TV (Chromecast with Google TV, Nvidia Shield, Nokia box) | Best performance | All IPTV apps in the Play Store. |
| Samsung / LG Smart TV | Good, fewer apps | Smart IPTV, IPTV Smarters, Set IPTV, IBO Player. MAC-based activation. |
| MAG box (Infomir) | Good for portal subscriptions | Common in the UK; uses a portal URL rather than M3U. |
| Enigma2 (Zgemma, Vu+) | Enthusiast | Loads IPTV via bouquets or XStreamity. |
| Apple TV / iPhone / iPad | Good | IPTV Smarters, GSE, iPlayTV. |
| Sky Glass / Sky Stream | Not suitable | Closed platform, no third-party IPTV apps. Add a Firestick to the TV's HDMI. |

Which app for which device: [awesome-iptv-players](https://github.com/smartvpro-tv/awesome-iptv-players). Step-by-step installs: [iptv-setup-guides](https://github.com/smartvpro-tv/iptv-setup-guides).

## Broadband speed you need

| Quality | Per stream | Comfortable household plan |
|---|---|---|
| SD | 5 Mbps | 20 Mbps |
| HD | 10–15 Mbps | 35–50 Mbps (standard fibre) |
| 4K | 25–35 Mbps | 100 Mbps (full fibre) |

Most UK buffering comes from Wi-Fi, not the broadband package. Run an Ethernet cable or powerline adapter to the TV. More fixes in [iptv-troubleshooting](https://github.com/smartvpro-tv/iptv-troubleshooting).

To measure the real speed between your home and the stream itself, for example during a Saturday 3pm kick-off, use the free [iptv-toolkit](https://github.com/smartvpro-tv/iptv-toolkit) and follow the [IPTV UK testing guide](https://smartvpro-tv.github.io/iptv-toolkit/uk.html).

## ISP blocking and VPNs

UK ISPs are required by court orders to block certain IPTV servers, and the blocking is strongest around live Premier League matches on Saturday afternoons and Monday evenings. Symptoms: streams that work on mobile data but not at home, or that fail only at kick-off.

- A VPN with a UK server restores access in most cases, with minimal speed loss.
- Install it on the Firestick or Android box; on Samsung/LG TVs install it on the router instead.
- Changing DNS alone sometimes helps, but a VPN is more reliable.
- A VPN does nothing for an overloaded provider server.

## What to check before buying an IPTV subscription

Use this with any seller, including us:

- [ ] **Free trial** of 24–48 hours, tested on a Saturday at 3 pm if football matters to you.
- [ ] **Full channel list published**: Sky Sports, TNT Sports, BBC, ITV, Channel 4, Sky Cinema, plus any Irish, Indian, Pakistani, Polish or Arabic packages you need.
- [ ] **Connections** stated clearly: 1, 2 or more devices at once.
- [ ] **Login type** compatible with your device (M3U, Xtream, MAG portal, Enigma2 bouquet).
- [ ] **EPG** included and in UK time.
- [ ] **Catch-up** (typically 2–7 days) and **VOD** if you want them.
- [ ] **UK-based or UK-hours support** that answers in hours.
- [ ] **Refund policy** in writing, and a payment method you can dispute.
- [ ] **No lock-in to a branded app** that stops working if the seller disappears.

Red flags: lifetime deals, prices far below the market, no trial, no channel list, Telegram-only support.

A shorter, step-by-step version of this checklist: [How to choose an IPTV service in the UK](how-to-choose-an-iptv-service-in-the-uk.md).

## Common UK channel categories

- **Terrestrial:** BBC One/Two/Three/Four, ITV1–4, Channel 4, Channel 5, regional variants
- **Sports:** Sky Sports (Main Event, Premier League, Football, F1, Cricket, Golf), TNT Sports 1–4, Premier Sports, Eurosport, Racing TV, PPV boxing
- **Movies and entertainment:** Sky Cinema, Sky Atlantic, Sky Max, Sky Witness, Gold, Dave, Alibi
- **News:** BBC News, Sky News, GB News, TalkTV
- **Kids:** CBeebies, CBBC, Nick Jr, Cartoonito
- **International:** Irish (RTÉ, Virgin Media One), Indian, Pakistani, Polish, Turkish, Arabic, African packages
- **VOD:** films and box sets, sorted by genre

An example of how a UK list is organised: [smartvpro.co.uk/iptv-channels-uk](https://smartvpro.co.uk/iptv-channels-uk/).

## FAQ

**Is IPTV legal in the UK?**
The technology is legal (Sky Stream and iPlayer are IPTV). Watching content the service does not have the rights to is unlawful, and selling it is a criminal offence. The safe position is to use services that are transparent about what they offer and that stand behind a refund policy.

**Do I need a TV licence for IPTV?**
Yes, for any live TV. See [The TV licence](#the-tv-licence).

**Why does my IPTV stop during Premier League games?**
Either ISP blocking (fix with a VPN) or the provider's server cannot handle the load (fix by choosing a better provider). Test during a match on your trial.

**Firestick, MAG box or Android box?**
Firestick for most people. MAG if your provider is portal-based. An Nvidia Shield if you want 4K and the best picture.

**Can I use it in Spain or on holiday?**
Most services work abroad; a few restrict logins to the UK. Ask first.

**4K IPTV: is it worth it?**
Only with a 4K TV, a 4K-capable device and 100 Mbps broadband. See [4K IPTV UK](https://smartvpro.co.uk/4k-iptv-uk/).

## Local guides by city

- [London](https://smartvpro.co.uk/iptv-london/)
- [Manchester](https://smartvpro.co.uk/iptv-manchester/)
- [Birmingham](https://smartvpro.co.uk/iptv-birmingham/)
- [Glasgow](https://smartvpro.co.uk/iptv-glasgow/)
- [Newcastle](https://smartvpro.co.uk/iptv-newcastle/)

## Further reading

- [How to choose an IPTV service in the UK: a practical 2026 checklist](how-to-choose-an-iptv-service-in-the-uk.md)
- [Download this checklist as a PDF](https://smartvpro1.s3.us-east-2.amazonaws.com/iptv-uk-checklist-2026.pdf)
- [Best IPTV UK](https://smartvpro.co.uk/best-iptv-uk/)
- [IPTV box UK](https://smartvpro.co.uk/iptv-box-uk/)
- [IPTV Smarters Pro UK setup](https://smartvpro.co.uk/iptv-smarters-pro-uk/)
- [IPTV free trial UK](https://smartvpro.co.uk/iptv-trial-uk/)
- [Video tutorials on YouTube](https://www.youtube.com/@SmartVProTV)
- Sister guides: [iptv-usa](https://github.com/smartvpro-tv/iptv-usa), [iptv-canada](https://github.com/smartvpro-tv/iptv-canada), [iptv-nederland](https://github.com/smartvpro-tv/iptv-nederland)

## Legal

This repository contains text only. It hosts no streams, playlists, channel links or copyrighted content. Channel and brand names are used for identification. Use any IPTV service in accordance with UK law and the service's terms.

Text licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
