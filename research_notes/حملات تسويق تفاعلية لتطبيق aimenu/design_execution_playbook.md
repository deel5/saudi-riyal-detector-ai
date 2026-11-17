# Design, Build and Measurement Playbook: "Lost Phone" Mystery/ARG and Other Interactive Formats for a Food-Delivery / AI-Menu App

Research note (Nov 2026). Network limits: en.wikipedia.org and gamedeveloper.com could not be fetched from this session. Findings drawn from those domains come from search-result snippets only and are marked as such. Most engagement benchmarks come from vendors' own data, so treat them as directional.

## 1. Format options and their tradeoffs

### Takeaway
A web-based "found phone" simulator (mobile web, no install) is the format with the most precedent and the most control: the indie "lost phone" game genre and several brand microsites show it works. Physical seeding (QR codes on delivery bags, planted props) and social or WhatsApp extensions add reach and realism, but they bring more operational and safety risk. LLM chatbot characters are the most engaging-sounding option and also the riskiest for brand safety.

### Cited Findings
**The "lost phone" genre (proof that the mechanic works)**
- *A Normal Lost Phone*: the player finds a smartphone and works out the owner's story by exploring apps, messages, emails and photos. It began as a game-jam prototype, and the team later identified design mistakes that they fixed in the sequel. One review praised how it "leverag[es] voyeurism, curiosity, responsibility, and compassion" with "satisfying puzzle-solving." — [Steam](https://store.steampowered.com/app/523210/A_Normal_Lost_Phone/); [Pocket Gamer review](https://www.pocketgamer.com/articles/072818/a-normal-lost-phone-review-a-mobile-based-narrative-adventure/); [Killscreen](https://www.killscreen.com/normal-lost-phone-aims-find-personal-stories-digital-lives/)
- RAWG lists the average playtime of A Normal Lost Phone as about 2 hours. That is far longer than any marketing experience should be. — [RAWG](https://rawg.io/games/a-normal-lost-phone)
- SIMULACRA (Kaigan Games) is a horror narrative played entirely through a phone interface. The developers cite SOMI's *Replica*, A Normal Lost Phone and the Mr Robot game *1.51exfiltrati0n* as sources of insight into "what mechanics worked and what didn't." The full article on turning phone UX into game mechanics could not be fetched; only the snippet was read. — [Game Developer deep dive](https://www.gamedeveloper.com/design/deep-dive-turning-phone-ux-into-game-mechanics-in-horror-game-i-simulacra-2-i-); [Destructoid](https://destructoid.com/simulacra-brings-horror-to-the-lost-phone-genre)

**Brand "lost phone" campaigns**
- Lost Phone Experiment (Netherlands): 100 phones were planted around the country and their fate was tracked on a microsite. It drew about 10,000 site visits in 6 days, with an average time on site of about 4.5 minutes. — [Cannes Lions / Love The Work](https://lovethework.com/work-awards/campaigns/lost-phone-236786) (from the search summary; the entry was not opened)
- "Phone-y Brew" (Nova Scotia tourism): a fake phone was used as a lure, and 64% of visitors reportedly clicked through from it to the tourism pages. — [IEEE Spectrum](https://spectrum.ieee.org/phoney-brew-2650251768)
- Time Out Shanghai "Stolen Phone Tour" (Energy BBDO): a real phone was left on a street. Text messages guided whoever found it through a night out, and hidden cameras filmed each stop. This is an example of a real-world, one-to-one physical stunt that is then amplified on video. — [Campaign Brief Asia](https://campaignbriefasia.com/?p=57605); [MediaPost](https://www.mediapost.com/publications/article/211236/time-out-shanghai-campaign-finding-lost-phone-.html); [Campaign Asia](https://www.campaignasia.com/video/time-out-magazine-loses-cell-phone-in-shanghai-guerrilla-campaign/349649)
- A cautionary example: Boogie's "Chute" stunt pitched a fake app to reporters as if it were real, and the coverage condemned it: "That's not hilarious viral marketing—it's just lying." — [Daily Dot](https://dailydot.com/?p=89339)

**Large-scale ARG precedent**
- *Why So Serious?* (42 Entertainment for The Dark Knight) reports more than 10M unique active participants (Cannes) or 11M (42 Entertainment) in more than 75 countries, over 14–15 months. It won a Cannes Titanium/Grand Prix. Mechanics included phone numbers written in the sky, GPS coordinates, puzzles and countdowns. An IJOC paper notes that the participant numbers come from the producers and were not independently verified. — [42 Entertainment](https://42entertainment.com/work/whysoserious); [Guinness](https://guinnessworldrecords.com/world-records/98707-most-popular-alternate-reality-game-arg); [Cannes entry](https://www.lovethework.com/work-awards/entries/why-so-serious-314294); [IJOC](https://ijoc.org/index.php/ijoc/article/download/803/503)
- *The Beast* (2001, for Spielberg's A.I.) is often called one of the first successful ARGs. Its first clues (the "rabbit hole") were hidden in the film's promotional material. — [HowStuffWorks](https://electronics.howstuffworks.com/alternate-reality-gaming.htm)

**AR lenses (Snapchat or Instagram)**
- Average playtime for sponsored lenses varies widely: Levi's 89 s, Foot Locker 45 s, Taco Bell 24 s (224M views, 48M uniques in one day), McDonald's Nordics about 14 s with a 5% share rate, Dairy Queen 10+ s. — [Digiday](https://digiday.com/marketing/500k-snapchats-ar-ads-now-cheap-luring-smaller-advertisers/); [Webtonic food service stats](https://www.webtonic.io/blog/food-service-catering-snapchat-ads-statistics) (vendor roundup)
- Costs: an older figure puts branded lenses at about $40k per day plus an $8–20 CPM. A 2026 roundup puts the median AR lens CPM at $13.80. Neither number comes from Snapchat's official rate card. — [Digiday](https://digiday.com/marketing/snapchats-programmatic-ar-ads/); [Webtonic](https://www.webtonic.io/blog/snapchat-ads)
- McDonald's "Taste the Future" let customers scan packaging to unlock AR features. It is a precedent for packaging as the trigger for an interactive experience. — [Agility PR](https://www.agilitypr.com/pr-news/content-media-relations/stellar-big-brand-food-and-beverage-digital-campaigns-of-2025-including-mcdonalds-and-coca-cola/)
- Food and beverage campaigns that worked in 2025 "all gave people a reason to participate, not just a product to look at." — [Homemade Social](https://www.homemadesocial.com/blog/food-and-beverage-social-campaigns-2025)

**WhatsApp chatbot narratives**
- Meta charges per message, and rates change only on quarter dates. Secondary sources put Saudi Arabia from 1 Oct 2026 at about USD 0.0576 per marketing template message and about USD 0.0107 per utility or authentication message. SAR became a billing currency on 1 Apr 2026. Check these figures against Meta's official rate card. — [Meta pricing docs](https://developers.facebook.com/docs/whatsapp/pricing); [LetsBot KSA guide](https://letsbot.net/en/blogs/whatsapp-business-api-pricing-ksa-2026-guide.html); [YCloud](https://www.ycloud.com/blog/whatsapp-api-message-pricing-update-effective-october-1-2026); [EngageLab](https://www.engagelab.com/blog/whatsapp-business-api-pricing)

**QR codes on packaging and delivery bags**
- In a 2025 GS1 US survey, 66% of consumers said they would scan a QR code on food packaging for information. — [QR roundup citing GS1 US](https://www.qrcode-tiger.com/qr-code-scanning-trends-in-retail-and-ecommerce) (secondary)
- Uniqode's State of QR Codes 2026: restaurants are the top place people scan (58%), then websites (42%) and product packaging (40%). 70% scan at least monthly and 58% are confident QR codes are safe. Top complaints are codes that fail to scan (36%) and expired links (29%). — [Uniqode 2026](https://www.uniqode.com/unique-angles/playbooks/state-of-qr-codes-2026/consumer-behaviour)
- Nearly 95% of QR scans come from just 5% of codes, so creative and placement decide most of the outcome. — [Retail Brew](https://www.retailbrew.com/stories/nearly-95-of-qr-code-scans-come-from-just-5-of-codes-what-gets-consumers-to-scan)

### Inferences
- For an AI-menu or delivery app, a comparison of the formats (my synthesis):
  - **Mobile-web phone simulator.** Best control, measurability and depth; no install friction. Cost is medium. It needs a distribution layer such as ads, influencers or QR codes.
  - **QR codes on delivery bags or receipts.** Reach existing customers for almost nothing and are good for retention or reactivation. Poor for acquiring new users unless bags are seen in public.
  - **Real Instagram or TikTok "found phone" accounts.** Native reach and UGC potential, but the highest risk of deception or confusion, and platform rules on inauthentic accounts may apply.
  - **WhatsApp narrative.** Very high open rates in KSA, but costs scale with messages. Business-initiated template messages need opt-in.
  - **AR lens.** Strong for awareness and sharing, but sessions are short (10–90 s) and it cannot carry a multi-clue mystery.
  - **LLM NPC.** Novel and fits the "AI menu" positioning, but carries the highest brand-safety risk (see section 5).
  - **Hotline or IVR.** Good for atmosphere (a voicemail clue) and cheap with Twilio-style numbers. Weak for analytics.
- The "lost phone" genre's 2-hour playtime has to be cut to roughly 5–10 minutes for a marketing build. The Lost Phone Experiment's 4.5-minute average time on site is a realistic target.

### Gaps
- No published benchmarks for "found phone" Instagram or TikTok accounts run by brands.
- No food-delivery ARG case study with a Discord or Reddit community turned up (the search found none for 2025).

## 2. ARG design principles (rabbit hole, TINAG, difficulty, breadcrumbing, community, pacing, payoff)

### Takeaway
ARGs depend on several entry points (trailheads), a story that comes before the puzzles, collaborative solving, deliberate bottlenecks that set the pace, and a payoff. For a brand in 2026, pure "This Is Not A Game" deception is ethically and reputationally risky. Use clear but low-key disclosure, such as an in-world brand signature and a visible "a game by AIMenu" footer.

### Cited Findings
- **Rabbit holes and trailheads:** the rabbit hole is the first artifact that draws players in. Most ARGs use several trailheads across different media to raise the odds of discovery. Websites are the usual choice because they are cheap and easy to update. Rabbit holes can be explicit or disguised, and should introduce the plot, theme and characters as well as the gameplay. Drawback: "it can take a painfully long time for people to notice a rabbit hole." — [CORE academic paper](https://core.ac.uk/download/212986348.pdf); [eLearning Industry: ARG pre-production](https://elearningindustry.com/advertise/elearning-marketing-resources/blog/how-to-make-an-alternate-reality-game-pre-production); [eLearning Industry: 10 tips](https://elearningindustry.com/arg-development-10-tips-to-create-an-effective-arg-story)
- **Story first:** a co-creator of the Frog Fractions 2 ARG said the primary goal "shouldn't be to present puzzles, but should be to present a compelling alternate reality." — [Game Developer](https://gamedeveloper.com/business/-i-frog-fractions-2-i-arg-co-creator-reflects-on-what-makes-a-good-alternate-reality-game) (snippet)
- **Collaborative solving:** Frank Lantz (area/code) at GDC named "collaborative puzzle solving, rather than competition" as a defining quality of a bona fide ARG. Players who simply played the casual layer were also unlocking meaningful fiction, which argues for building more than one depth layer. — [Game Developer: GDC Lantz](https://www.gamedeveloper.com/game-platforms/gdc-frank-lantz-on-creating-area-code-s-i-chain-factor-i-) (snippet)
- **Bottlenecks and pacing:** ARG puzzle design guidance recommends "designing particular bottlenecks which gate entrance to the next stages." — [Game Developer: ARG puzzle design](https://gamedeveloper.com/design/alternate-reality-game-puzzle-design) (snippet). Puzzle dependency graphs (Ron Gilbert, GDC 2016; Noah Falstein, GDC 2013) help visualize non-linear branching so difficulty and pacing can be tuned. — [Puzzle dependency graph primer](https://gamedeveloper.com/design/puzzle-dependency-graph-primer)
- **Difficulty and fairness:** Grant Elyot's GDC 2025 slides list "balance and pacing" as core concerns, note that struggling with something difficult is tiring, and recommend "forward design," which builds the puzzle logic in the order the solver will meet it. — [GDC 2025 slides PDF](https://media.gdcvault.com/gdc2025/Slides/Grant_Elyot_Designing+10%2C000+Puzzles.pdf). Clara Fernandez-Vara: respect "the contract with the player to provide a fair puzzle." — [Game Developer: GDC Online](https://gamedeveloper.com/design/gdc-online-making-puzzles-and-writing-work-together). Wrong answers should get clear feedback that explains why they fail. — [Remap Radio on Cocoon](https://remapradio.com/articles/a-house-of-cards-built-on-trust-puzzle-design-in-cocoon-2/)
- **Community and serialization:** one practitioner checklist advises designing for long-term community "as a marathon with serialized content, evergreen puzzles, and seasonal restarts," and lists conversion to email or Discord sign-ups as a KPI. — [linking.live ARG checklist](https://linking.live/step-by-step-launch-an-alternate-reality-game-to-boost-your-) (practitioner blog, lower authority)
- **Community design:** GDC has scheduled a session titled "Designing ARGs to Foster Meaningful Community Connection." — [GDC schedule](https://schedule.gdconf.com/session/designing-args-to-foster-meaningful-community-connection/918336) (content not reviewed)
- **TINAG and trust:** purists say players should at least at first be fooled by the rabbit hole. — [blog via search](https://iumm.blogspot.ca). Community voices add that "very few players will provide you their trust without having yours first." — [Unfiction forum archive](https://unforum-archive.netninja.com/forums/viewtopic.php@p=223581.html). An academic paper examines how ARGs can slide into "participatory propaganda" on social platforms. — [Bortnick, ELO 2021](https://conferences.au.dk/fileadmin/conferences/2021/ELO2021/Full_papers/Justin_Bortnick_Dangerous_Games__ARGs__Social_Media_Platforms_and_Participatory_Propaganda__126.pdf)
- **Henry Jenkins on "ARG 2.0":** a discussion of how the form has evolved. — [henryjenkins.org](https://www.henryjenkins.org/blog/2010/07/arg_20_1.html)

### Inferences
- Suggested structure for an AIMenu "lost phone":
  - **Day 0 trailheads.** A QR code on the bag ("Found this phone in my order?"), an influencer seeding post, and a paid teaser.
  - **Layer 1, casual.** Browse photos, chats and notes and find 3 clues (restaurant names, dishes, times). About 5 minutes. Completers get a small promo code.
  - **Layer 2, hard.** A cipher across apps: a map pin plus call-log times plus a dish order unlocks a passcode. Gate it with a daily drop over 5–7 days, and feed new chat messages to the phone each day.
  - **Payoff.** A finale reveal, for example the phone owner's last order turns out to be an AIMenu "mystery dish." The reward must be redeemable only in the app (deep-linked promo).
- Use phone-native gating that draws on real UX: a lock-screen passcode found in a photo, notes app passwords, a "search" field in chats, and a map timeline. Give hints on a timer (for example, a hint button after 60 s with no progress) so casual users don't drop off.
- Disclosure: avoid full TINAG. Use a lightly branded splash ("An AIMenu mystery") or a persistent footer, and never use real names or real numbers.

### Gaps
- No sourced data on what share of an ARG audience solves the hard layer compared with consuming the casual layer. Practitioner lore is the "1–9–90" pattern, but I found no citation for it.
- The ARG ethics article (criticalvideogamestudies.com) returned no usable text.

## 3. Tools and tech stack

### Takeaway
A phone simulator can be built with Twine or Ink (narrative logic) inside a custom HTML/CSS phone shell, or prototyped quickly in Figma. Deep links with deferred deep linking (AppsFlyer OneLink, Adjust, Branch) are the critical link between the game and app installs or orders. WhatsApp narratives run on the WhatsApp Business Platform through a BSP.

### Cited Findings
- **Twine** is free, open source, popular for web IF and visual ("sticky notes and string"), and easier to restyle than Ink's default web export. **Ink/Inky** is a more powerful scripting language aimed at professional game development, and its web export is harder to customize. **inklewriter** is the simplest option, and Inkle historically retained some control over stories. — [Inkle web tutorial](https://www.inklestudios.com/ink/web-tutorial/); [inklestudios.com/ink](https://inklestudios.com/ink/); [intfiction.org thread](https://intfiction.org/t/ink-inky/80845); [Emily Short on Twine](https://emshort.blog/2012/11/10/choice-based-narrative-tools-twine/); [AlternativeTo](https://alternativeto.net/software/inklewriter)
- **AppsFlyer OneLink** supports a "QR-to-app" experience. Deferred deep linking carries campaign context through the app-store install, so a user who scans a QR code and installs lands on the right page after install. It works across QR codes, social, email and SMS. Install attribution requires the AppsFlyer SDK. Probabilistic matching can fail. On iOS 14.5+, the legacy deferred deep linking method may fail, and Unified Deep Linking (UDL) is recommended. — [AppsFlyer QR-to-app](https://www.appsflyer.com/products/deep-linking/qr-to-app/); [Deferred deep linking glossary](https://appsflyer.com/glossary/deferred-deep-linking); [OneLink support](https://support.appsflyer.com/hc/articles/208874366); [iOS legacy APIs](https://dev.appsflyer.com/hc/docs/dl_ios_gcd_legacy)
- Vendor case studies: Albertsons reported 1.2M+ QR visitors in 2 months and a 113% rise in app traffic. Letyshops reported 700k+ installs and 25–40% conversion using OneLink with influencers and 112 QR codes. — [AppsFlyer QR-to-app](https://www.appsflyer.com/products/deep-linking/qr-to-app/); [casestudies.com Letyshops](https://www.casestudies.com/company/appsflyer/case-study/improving-user-acquisition-and-customer-experience-with-onelink)
- **Measuring sharing:** Riddle reports that 78% of shares of interactive content escape web analytics (dark social), so share counts in GA undercount. — [PPC Land](https://ppc.land/riddle-finds-78-of-interactive-content-shares-escape-web-analytics/)

### Inferences
- Recommended stack:
  - Next.js or plain HTML phone UI, built mobile-first with RTL Arabic support.
  - Narrative state in JSON, Twine or Ink.
  - Analytics with GA4 or Mixpanel/Amplitude, tracking events per app opened, per clue found and per puzzle solved.
  - OneLink or Adjust for the CTA to install or order, with a unique promo code per completer so attribution works even when the SDK fails.
  - Hosting on Vercel or Netlify.
  - Optional WhatsApp flow through a BSP such as 360dialog or Twilio.
  - Optional LLM character behind strict guardrails.
- No-code prototype options: Figma interactive prototypes for testing; Typeform or Outgrow for a "who owns this phone?" quiz ending; Webflow for the landing page.
- Rough cost and time ranges (my inference; no sourced rate cards were found):
  - Figma or no-code prototype: 1–2 weeks.
  - Custom web phone simulator with 6–8 apps and Arabic/English: about 4–8 weeks with a small team.
  - Multi-week live ARG with daily drops, community moderation and physical props: 8–12+ weeks of preparation plus live operations.
  - Media and seeding typically match or exceed the build cost.

### Gaps
- No sourced agency price ranges for ARG or interactive microsite builds in the GCC. Get these from agency quotes.
- Adjust and Branch documentation was not reviewed. They have equivalent deferred deep-link features (not verified here).

## 4. KPIs and benchmarks

### Takeaway
Measure a funnel: reach → starts → depth (apps opened, clues found) → completion → share/UGC → promo redemption or install → first order → retention. Vendor benchmarks for interactive quizzes suggest 60–85% completion for short experiences and roughly 40% start-to-lead. Lens playtime runs 10–90 s. A phone microsite precedent averaged about 4.5 min on site.

### Cited Findings
- **Quizzes:** Interact reports 40.1% start-to-lead and 65% start-to-finish, stable since 2014. — [Interact report](https://tryinteract.com/blog/quiz-conversion-rate-report/). Outgrow's 2026 benchmarks suggest more than 70% completion for quizzes and 35–55% of completers giving contact details, and note that benchmarks depend on length and purpose. — [Outgrow](https://outgrow.co/blog/user-engagement-benchmarks/). Pinpoll: 87% of quiz starters finish, and 68% of finishers leave data. — [Pinpoll help](https://help.pinpoll.com/en/articles/8617091-what-do-the-quiz-numbers-tell-us)
- **Interactive vs passive:** one summary of a 2024 Demand Metric report claims 2.7× more engagement for interactive content, and 18.3% conversion for configurators against 7.6% for static pages. Not verified against the original. — [Webtonic](https://www.webtonic.io/blog/interactive-marketing-statistics)
- **Lenses:** judge lenses on lens-specific KPIs (playtime, share rate), not feed-ad norms. — [Webtonic](https://www.webtonic.io/blog/snapchat-ads); playtimes and share rates are listed in section 1.
- **Phone microsite:** about 10,000 visits in 6 days, about 4.5 min average. — [Love The Work](https://lovethework.com/work-awards/campaigns/lost-phone-236786)
- **Fake-phone click-through:** 64% clicked from the fake phone to the destination pages. — [IEEE Spectrum](https://spectrum.ieee.org/phoney-brew-2650251768)
- **Dark social:** 78% of interactive shares escape analytics. — [PPC Land / Riddle](https://ppc.land/riddle-finds-78-of-interactive-content-shares-escape-web-analytics/)
- **Offline-to-app:** Letyshops reported 25–40% conversion rates (vendor). — [casestudies.com](https://www.casestudies.com/company/appsflyer/case-study/improving-user-acquisition-and-customer-experience-with-onelink)

### Inferences
- Suggested KPI targets for a v1 (my inference; calibrate during a pilot):
  - Start rate from landing page: ≥50%.
  - Median session: 3–6 min.
  - Layer 1 completion: ≥40% of starters.
  - Promo-code reveal to redemption: track separately.
  - Share rate: ≥5%, matching the McDonald's lens share rate.
  - Include a "copy link / share to WhatsApp" button with UTM parameters, plus unique codes to capture dark-social sharing.
- Calculate effective CAC as (build + media + reward cost) ÷ first orders attributed through unique codes and OneLink. Compare it with the app's paid-social CAC baseline.
- Instrument the per-app heatmap (which fake apps get opened) and drop-off by clue. These are the design-iteration levers.

### Gaps
- No independent, non-vendor benchmark for ARG completion rates or ARG-to-install conversion.
- No public CAC figures for interactive or ARG campaigns in food delivery.
- No Nielsen or eMarketer primary study on interactive content was retrieved.

## 5. Risks and pitfalls

### Takeaway
The biggest risks for a "lost phone" concept: it looks like a real privacy breach or a phishing scam (lost-iPhone phishing is a live, current scam pattern); deception backlash; LLM characters being jailbroken; puzzles that are too hard; and low discovery without seeding. Accessibility and Arabic RTL support are often overlooked.

### Cited Findings
- **Phishing confusion:** "lost iPhone" phishing is active. Victims receive texts pretending their lost phone was found, which lead to fake iCloud login pages. Switzerland's NCSC flagged "Lost iPhone – the phishing trap that follows" in 2025. A fictional "found phone" message or QR code can resemble these scams. — [NCSC Switzerland week 44 2025](https://www.ncsc.admin.ch/ncsc/en/home/aktuell/im-fokus/2025/wochenrueckblick_44.html); [CSO Online](https://www.csoonline.com/article/550772/iphone-theft-victims-tricked-into-unlocking-devices.html); [Yahoo News](https://www.yahoo.com/news/articles/sneaky-scam-targeting-iphone-users-120017448.html)
- **QR trust:** only 58% of consumers are confident QR codes are safe, and dead links (29%) and failed scans (36%) are top complaints. — [Uniqode 2026](https://www.uniqode.com/unique-angles/playbooks/state-of-qr-codes-2026/consumer-behaviour)
- **Deception backlash:** a fake app presented as real was condemned as "just lying." — [Daily Dot](https://dailydot.com/?p=89339). Misleading marketing (The Day Before) destroyed creators' credibility. — [USC VCE](https://vce.usc.edu/weekly-news-profile/the-day-before-the-ethical-lesson-of-misleading-game-marketing/)
- **LLM character brand safety:** a customer got DPD's chatbot to swear and call DPD the "worst delivery firm." The story reached about 800k views in 24 hours, and DPD disabled the AI element. — [Fox Business](https://foxbusiness.com/technology/dpd-ai-error-causes-chatbot-swear-calls-itself-worst-delivery-service-disgruntled-user-report); [Fortune](https://fortune.com/europe/2024/01/22/ai-chatbot-delivery-calls-itself-useless-works-for-worst-firm-in-world/amp/); [AI Incident DB #631](https://incidentdatabase.ai/cite/631/). Gap's Sierra-built chatbot was jailbroken into discussing sex toys and Nazi Germany as part of a coordinated attack on more than a dozen clients' agents. — [eMarketer](https://www.emarketer.com/content/gap-chatbot-jailbreak-brand-safety-risk). Chipotle's agent was steered into answering coding questions (Mar 2026). — [CX Foundation](https://cxfoundation.com/news/chipotle-agent-goes-off-the-rails). One report says customer chatbots are "almost certainly insecure." — [SecurityWeek](https://www.securityweek.com/beware-your-customer-chatbot-is-almost-certainly-insecure-report/amp/)
- **Slow discovery:** rabbit holes can take "a painfully long time" to be noticed, so several trailheads are needed. — [CORE paper](https://core.ac.uk/download/212986348.pdf)
- **Difficulty fatigue:** "struggling with something difficult is tiring." — [GDC 2025 slides](https://media.gdcvault.com/gdc2025/Slides/Grant_Elyot_Designing+10%2C000+Puzzles.pdf)
- **ARGs on social platforms** can blur into misinformation or "participatory propaganda." — [Bortnick ELO 2021](https://conferences.au.dk/fileadmin/conferences/2021/ELO2021/Full_papers/Justin_Bortnick_Dangerous_Games__ARGs__Social_Media_Platforms_and_Participatory_Propaganda__126.pdf)

### Inferences
- Mitigations:
  - Never ask for logins, passwords or payment inside the fiction.
  - Never send unsolicited "we found your phone" SMS messages.
  - Host on a clearly branded domain (for example, mystery.aimenu.app), not a lookalike.
  - Put the brand on the QR card and bag.
  - Use fictional names, numbers and faces (stock or AI imagery with rights cleared). Avoid real addresses on the map.
  - Avoid crime or violence themes. A "missing dinner order" or "secret recipe" mystery suits the Saudi audience better than a "missing person" one.
  - Plan for real-world confusion: physically planted phones may be handed to police, and fictional numbers may get called. Use owned numbers.
- LLM NPC guardrails:
  - Use a narrow persona prompt plus input and output moderation.
  - Restrict the character to story topics, cap tokens, refuse off-topic requests, and log and red-team before launch.
  - Consider scripted branching (Twine or Ink) with LLM used only for flavor text.
- Accessibility: provide alt text for "photos," real buttons rather than gesture-only controls, and sufficient contrast. Don't rely on audio-only clues. Support Arabic RTL and font sizes. Offer a "story mode" that skips puzzles.
- Difficulty: playtest with 10–20 target users. Aim for 80% of testers to finish layer 1 without help, and keep hard puzzles optional.

### Gaps
- No sourced specifics on Saudi regulations (PDPL data-protection law, GCAM or CST advertising-disclosure rules, or SAMA rules on promotions and competitions) as they apply to ARGs or prize mechanics. This needs local legal review.
- No documented incident of a brand "lost phone" campaign being mistaken for a real breach was found, so the risk above is inferred from the phishing pattern.
