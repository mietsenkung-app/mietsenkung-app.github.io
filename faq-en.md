---
layout: default
title: FAQ — RentReducer
description: All answers about rent reduction, the request letter, follow-up letters, and conciliation in Switzerland. Privacy, pricing, tenant protection.
lang: en-CH
permalink: /faq-en.html
---

<div class="lang-switch">
  <a href="faq-de.html">DE</a>
  <a href="faq-fr.html">FR</a>
  <a href="faq-it.html">IT</a>
  <span class="active" aria-current="page">EN</span>
</div>

# All frequently asked questions about RentReducer

Here you find answers to all topics around the app: claim calculation, sending the letter, follow-up letters, conciliation procedure, data protection, pricing, tenant protection under Art. 271a CO, and more.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "When am I entitled to a rent reduction?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "As soon as the reference interest rate has dropped since your last rent adjustment or the start of your tenancy (Art. 270a CO). The reduction is not automatic. You have to actively request it from your landlord. RentReducer checks for you whether you currently have a claim and calculates the amount right after you enter your net rent and the last adjustment date."
      }
    },
    {
      "@type": "Question",
      "name": "How does the app calculate my claim?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "RentReducer follows the Swiss Tenancy Ordinance OBLF (Art. 13) and the Swiss Code of Obligations CO (Art. 269a). Three factors go into the calculation: (1) Reference rate drop, for every 0.25 % drop in the rate, rent decreases by 2.91 % (the conservative minimum per OBLF); for multiple steps, we apply the inverse of the cumulative increase. (2) General cost increase, 0.5 % per year since the last adjustment, which your landlord is allowed to offset against the reduction. (3) Inflation compensation, 40 % of the CPI (consumer price index) change since the last adjustment, also charged against the reduction. Your net claim is: reference rate drop minus cost increase minus inflation. If the result is negative, you have no claim, even if the rate dropped. For a binding calculation, contact the tenants' association."
      }
    },
    {
      "@type": "Question",
      "name": "Where do the reference rate and inflation data come from?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The reference rate is published by the Federal Office for Housing FOH (quarterly updates, sometimes unchanged carry-overs). The consumer price index (CPI) for inflation comes from the Swiss Federal Statistical Office FSO (monthly, released around the 6th of the following month). Both sources are legally binding. RentReducer fetches the current values on every start from the server (not from the app download), and we update them as soon as the FOH or FSO publishes a new value. If our data is ever out of date, you will see a discreet notice on the dashboard. You can check the raw data anytime at bwo.admin.ch and bfs.admin.ch."
      }
    },
    {
      "@type": "Question",
      "name": "Why does the app sometimes say \"no reduction claim\" even though the reference rate dropped?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For long-running leases (e.g. 10 years since the last adjustment), accumulated inflation (~1 % per year) plus cost increases (0.5 % per year) can be offset by your landlord against your reduction request. Result: rate drop + accumulated offsets = no net claim. RentReducer shows this case honestly so you don't send a letter your landlord could rightly reject. If you have doubts, or if the cost increase has already been offset by an earlier reduction, clarify with the tenants' association."
      }
    },
    {
      "@type": "Question",
      "name": "What about indexed or stepped rental contracts?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For these contract types, a reduction based on the reference rate is excluded during the contract term. RentReducer does not detect the contract type automatically, you have to check briefly yourself.  How to identify your contract type:  - Standard rental contract (most common, about 90-95% of Swiss residential leases): rent is a fixed CHF amount per month, no index linkage and no pre-defined increases. Example: \"Net rent CHF 1500 per month\". → Reduction request under Art. 270a CO is possible. - Indexed contract: rent is explicitly tied to the Swiss Consumer Price Index (CPI) and rises with inflation. Contract keywords: \"indexed rent\", \"CPI linkage\", \"adjustment to the national index\". Precondition: a lease with at least 5 years fixed duration (Art. 269b CO). → No reduction based on the reference rate. - Stepped rent contract: rent increases according to a plan fixed in the contract, e.g., \"Year 1 CHF 1500, Year 2 CHF 1550, Year 3 CHF 1600\". Contract keywords: \"stepped rent\", \"agreed rent steps\". Precondition: minimum duration of 3 years (Art. 269c CO). → No reduction based on the reference rate.  If in doubt, the tenants' association in your canton (mieterverband.ch) can verify your contract."
      }
    },
    {
      "@type": "Question",
      "name": "Can I claim the reduction retroactively?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. The reduction only takes effect from the next termination date after your request. Amounts overpaid in the past cannot be recovered. That's exactly why RentReducer offers the rate alert: we notify you as soon as the reference rate drops. So you never miss a reduction."
      }
    },
    {
      "@type": "Question",
      "name": "How do I find the date of the last adjustment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Check your rental contract and any later letters from your landlord (often on the official form). The last adjustment may be the start of the tenancy if there's been none. If unsure, choose \"I'm not sure\" in the wizard. RentReducer calculates conservatively with an estimate."
      }
    },
    {
      "@type": "Question",
      "name": "When does the new, lower rent take effect?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The reduction takes effect on the next possible termination date after the contractual notice period (usually 3 months). If you file early enough, it applies to that date. RentReducer uses the 4 common Swiss quarter-ends by default (31.03 / 30.06 / 30.09 / 31.12) and automatically inserts the next possible date into the letter."
      }
    },
    {
      "@type": "Question",
      "name": "When exactly does the letter have to reach my landlord?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The letter must arrive before the notice period starts. Example: for a reduction from July 1st with a three-month notice period, the letter has to reach the landlord by the end of March. Send it by registered mail for proof of delivery. RentReducer inserts the next possible date automatically; you just decide when to mail it."
      }
    },
    {
      "@type": "Question",
      "name": "Does my landlord have to respond to the letter?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Your landlord has to respond in writing within 30 days. If they agree, the rent is adjusted. The letter generated by RentReducer states the 30-day deadline and the legal basis (Art. 270a Swiss Code of Obligations CO, Art. 13 Swiss Tenancy Ordinance OBLF), so your request is formally correct."
      }
    },
    {
      "@type": "Question",
      "name": "How should I send the letter?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Registered mail is best. You get proof of delivery in case of dispute. RentReducer creates the PDF and you can send it directly from the app as a standard letter or as registered mail. Alternatively, download it as PDF or Word, print it and post it yourself. Always keep a copy for your records."
      }
    },
    {
      "@type": "Question",
      "name": "How do I send a letter directly from the app?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Create the letter in the wizard, open the preview and tap \"Send letter\" or \"Send Registered\". The first time, we ask for your signature (drawn once on the device). Then RentReducer hands the letter to the Swiss print service Pingen, which physically prints and posts it to your landlord. You receive a push notification the moment the letter is handed to Swiss Post, with registered mail, also on the day of delivery."
      }
    },
    {
      "@type": "Question",
      "name": "How do I know whether my letter actually arrived?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "As soon as Pingen (the Swiss letter-mailing service based in Zurich, pingen.com) hands your letter to Swiss Post, RentReducer sends you a push notification (\"Letter on its way\"). With registered mail (CHF 7.90 surcharge), you additionally receive a second push on the day of actual delivery (\"Letter delivered on DD.MM.\"), and the Swiss Post tracking number appears in the letter view. A standard send by definition provides no proof of delivery (this is a Swiss postal-system trait, not a limitation of the app). If you need legal certainty about arrival, e.g. because you may go to conciliation, choose registered mail."
      }
    },
    {
      "@type": "Question",
      "name": "What does sending cost?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Standard letter delivery is included directly in the letter purchase (no surcharge). No extra cost, delivery typically within 2 business days. Registered costs an additional CHF 7.90 per letter (surcharge, not included), payable via App Store / Play Store. The price covers postage, proof-of-deposit and printing. At the post counter, a registered letter costs about CHF 5.70 plus your trip. Registered mail is legally recommended for reduction requests because it provides proof of delivery."
      }
    },
    {
      "@type": "Question",
      "name": "Can I cancel a letter that's already been sent?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, within about 30 minutes of sending, as long as Pingen has not yet printed the letter. On the letter card in the dashboard a \"Cancel\" chip appears. Tap it, the letter is deleted at Pingen and goes back to draft in the app. You can then e.g. correct the recipient address and resend. If the letter is already printed, the app shows \"Cancellation no longer possible\", you then have to wait for the letter to come back (registered) or chalk it up as experience."
      }
    },
    {
      "@type": "Question",
      "name": "I marked the letter as self-delivered but did not post it. What now?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Tap the pencil icon on the letter card in the dashboard. The opening sheet shows a \"Reset self-send\" button. Confirm and the letter returns to draft status, the send date and any response status are removed. You can then resend it or download it as Word."
      }
    },
    {
      "@type": "Question",
      "name": "How do I bring back an archived process?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "In the More tab under \"Archive\" you find all completed processes. Per process group there is a \"Reactivate process\" icon (circular arrow) next to the delete icon. Tap → confirmation dialog → the letters of that process re-appear in the active dashboard, the current status (accepted/partial/rejected) is preserved. Useful if you e.g. want to take a closed process to conciliation after all."
      }
    },
    {
      "@type": "Question",
      "name": "My letter came back (undeliverable). What now?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "In the dashboard a \"Sending failed\" hero appears with a hint about a possible address error. Tap \"Check address\" → you land directly in the landlord form. Correct the address, save, return to the letter and resend. Note: \"undeliverable\" only comes back for registered mail, because Swiss Post does not track standard letters. For legal proof of delivery we recommend the registered upgrade (+ CHF 7.90)."
      }
    },
    {
      "@type": "Question",
      "name": "Can I send multiple reminder letters?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. If your landlord remains silent despite the first reminder, you can send a second (or third) reminder letter. Tap the reminder CTA as usual, the app shows a dialog \"Already sent on DD.MM., resend?\" and you confirm the purchase (CHF 6.90 per follow-up letter). Often legally meaningful as a last escalation before the conciliation petition, because multiple reminders document the process. Same logic for the documents request."
      }
    },
    {
      "@type": "Question",
      "name": "Does the conciliation authority accept my letter from RentReducer, or do I need a cantonal form?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The conciliation letter generated by RentReducer complies with Art. 202 para. 2 CPC: it contains the designation of the opposing party, the legal claim and the subject of the dispute, as well as your signature. It must therefore be accepted by all Swiss conciliation authorities in tenancy matters. There is no federal requirement to use a cantonal form.  Some cantons (e.g., Zurich, Berne) additionally offer their own conciliation forms to speed up internal processing. These forms are a recommendation, not a requirement. If your conciliation authority asks for a form: you can submit it later; your initial filing remains valid within the deadline (the date of the RentReducer letter counts for the 30-day deadline under Art. 273 CO).  If you prefer the cantonal form: contact the competent conciliation authority for your residence. Addresses are listed on bwo.admin.ch under \"Schlichtungsbehörden / Conciliation authorities\". In this case, download the conciliation letter from RentReducer as a Word file and transfer the calculations and attachment list into the form."
      }
    },
    {
      "@type": "Question",
      "name": "How do I track the conciliation hearing in the app?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Once you have sent the conciliation petition letter, a \"Proceedings timeline\" card appears under the letter with three phases. (1) Summons received: tap and enter the date you received the summons from the conciliation authority. (2) Hearing date: the date of the hearing itself. (3) Outcome: after the hearing pick \"Agreement reached\", \"Settlement concluded\" or \"Case goes to court\". You've now documented the proceedings in the app, parallel to your official files at the authority."
      }
    },
    {
      "@type": "Question",
      "name": "Can I edit the letter text?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, download the letter as Word (preview → download icon in the top right → Word). Important: as soon as you change the text in the Word file, you can no longer send the letter via RentReducer. You then need to print it and post it yourself. In-app sending only works with the original app text because the letter is handed to the print service before you could make any changes."
      }
    },
    {
      "@type": "Question",
      "name": "Is my in-app signature legally valid?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, for all letters in RentReducer it is sufficient. Swiss rental law (art. 270a CO) does not prescribe any particular form for reduction requests or follow-up letters. Your finger-drawn signature meets practical standards and is accepted by landlords. The signature is stored only locally on your device and transmitted to the print service only at send time."
      }
    },
    {
      "@type": "Question",
      "name": "Is a finger-drawn signature on the smartphone legally valid?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The rent reduction request is form-free under Art. 270a CO: no written form, no handwritten signature required. The finger-drawn signature in RentReducer therefore goes far beyond what is legally needed and is more than sufficient. The Federal Supreme Court confirmed in BGE 144 III 81 that a simple electronic signature is equivalent to a handwritten one for form-free legal transactions (see also Art. 13/14 CO on simple written form as the default for form-bound transactions). If the matter goes to a conciliation procedure, RentReducer already provides the necessary identification through your recorded personal details (name, address)."
      }
    },
    {
      "@type": "Question",
      "name": "Do all tenants need to sign?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Legally no, Swiss rental law prescribes no form. But it is strongly recommended in practice: landlords may refuse a request made by one person without the consent of the others. With multiple contract parties, RentReducer offers two paths: sign together on the device (the wizard passes the device between the parties) and send via the app, or download the letter, have it signed on paper and post it yourself."
      }
    },
    {
      "@type": "Question",
      "name": "Does RentReducer offer follow-up letters too?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Under \"Your letters\" on the dashboard you'll find, alongside the main reduction request, three follow-up letters: \"Reminder letter\" (if your landlord doesn't respond at all, happens often), \"Request explanation and evidence\" (if they refuse citing cost flat rates, local/district customariness or yield) and \"Apply for conciliation\" (if silence continues or the answer is insufficient). All letters come pre-filled with your data, available as PDF and editable Word document."
      }
    },
    {
      "@type": "Question",
      "name": "My landlord doesn't respond at all, what now?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Very common. Many (especially smaller) landlords simply don't react to a reduction request. After 30 days of silence you can legally go straight to the conciliation authority. But often it pays off to first send a friendly reminder with a final deadline. Under \"Your letters\" you'll find the \"Reminder letter\" follow-up for this: it confirms the date of your original letter, sets a new 14-day deadline, and announces that you'll file with the authority otherwise. Often this alone prompts a response and avoids escalation."
      }
    },
    {
      "@type": "Question",
      "name": "What can my landlord offset against my claim?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Two factors: 40 % of accumulated inflation and general cost increases (maintenance, administration, fees, property tax, insurance). The Federal Supreme Court requires landlords to prove cost increases via a comparative calculation. In practice, many conciliation authorities accept flat-rate offsets if tenants don't object. If you do challenge the flat rate, your landlord must document actual costs using 3- or 5-year averages. If your landlord argues with such a flat rate: under \"Your letters\" you'll find the \"Request explanation and evidence\" (CHF 6.90) follow-up to demand the evidence. RentReducer deliberately calculates without these deductions. Your net claim may end up lower."
      }
    },
    {
      "@type": "Question",
      "name": "What can I do if my request is refused?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You can file a petition with the conciliation authority of your district within 30 days of receiving the response. If your landlord doesn't reply or replies late, you have 60 days from the original letter's dispatch. The procedure is free. Common (often untenable) refusal reasons: insufficient yield, lack of local or neighbourhood customariness, excessive flat-rate cost offsets. Under \"Your letters\" you can create the appropriate follow-up letters: \"Request explanation and evidence\" for a refusal citing one of these reasons, \"Apply for conciliation\" to file with the authority. If in doubt, the tenants' association can help. RentReducer does not handle the conciliation itself."
      }
    },
    {
      "@type": "Question",
      "name": "Does RentReducer remind me if nothing happens?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. After you send the letter, RentReducer checks back automatically after 14, 30 and 60 days if your landlord did not respond. With one tap you set the status (accepted / partial / rejected / no response yet) and the app suggests the right follow-up letter directly. You do not have to write anything down in your calendar. We remind you until you say your case is done."
      }
    },
    {
      "@type": "Question",
      "name": "What does the app store on my device, and is my data safe?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Everything you enter, tenant, landlord, lease, letters and your signature, stays locally on your device, in an encrypted database (AES-256). The key lives in the Keychain (iOS) or Keystore (Android) and never leaves the device. When you send a letter, only the finished PDF is handed to Pingen (Swiss print service, signed AVV). No account, no cloud sync, no advertising IDs. You can wipe everything anytime via Settings → Privacy → \"Erase all my data\"."
      }
    },
    {
      "@type": "Question",
      "name": "How much does RentReducer cost?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You pay per letter, everything included, one tap. Checking your claim + the rate alert are free. To send the reduction letter you pay once between CHF 9.90 and 29.90 per letter. The price depends on your monthly savings (about 30 % of the first month's savings, floor 9.90, ceiling 29.90). Included: letter generation, printing, automatic letter dispatch via Pingen (Swiss letter-mailing service, pingen.com), push notification the moment the letter is on its way, automatic reminders after 14/30/60 days if no answer comes. No subscription, no recurring payments. Registered mail as an upgrade: + CHF 7.90, and you get a second push on the day of delivery. Follow-up letters: CHF 6.90 each if your landlord does not respond. Reminder and document-request go out automatically via Pingen. The conciliation announcement is also sent directly by RentReducer as of v1.0.x: you take a photo of the lease (mandatory attachment) and any further correspondence, the app auto-attaches copies of your previous letters, and the whole packet goes by registered mail (CHF 7.90 surcharge) to the conciliation authority. Alternatively you can still download the letter as Word and post it yourself."
      }
    },
    {
      "@type": "Question",
      "name": "Do I have to pay monthly or yearly?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. RentReducer is not a subscription. You pay once per letter. And only when you actually want to create one. No recurring access to your account, no cancellation to handle. If you become eligible again in a few years (a new drop of the reference rate), you can buy another letter. Again per letter, without anything running in the background."
      }
    },
    {
      "@type": "Question",
      "name": "What if I install RentReducer on a new device?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "If you reinstalled RentReducer or switched devices, you can recover your purchases via Settings → Restore purchases. Apple and Google provide the list of your prior purchases. RentReducer records them locally again."
      }
    },
    {
      "@type": "Question",
      "name": "Can I cancel a purchase or get a refund?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Letters are digital services delivered immediately: after you tap \"Send\", the letter goes to the printing service and is physically produced. A cancellation after sending is therefore not possible. If you paid but haven't sent (e.g. you closed the app before sending), you can request a refund through your App Store within 14 days. iOS: reportaproblem.apple.com → RentReducer → purchase → \"Report a Problem\". Android: play.google.com → Orders → RentReducer → \"Request a refund\". Apple and Google decide on the refund. RentReducer doesn't handle payments directly and cannot cancel a purchase on its own."
      }
    },
    {
      "@type": "Question",
      "name": "What happens to my data if I delete and reinstall the app?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Your letters, lease details, and signature are AES-256 encrypted and stored only on your device. The key lives in the iOS Keychain or Android Keystore and is tied to the installation. If you delete RentReducer, the key is deleted with it and the encrypted database becomes unreadable, even for the app makers. This is intentional: no cloud, no account, no trail. After reinstalling you can only restore your purchases (Apple/Google); your letters and inputs must be re-entered. Tip: download important letters as Word or PDF and back them up to your cloud storage or email them to yourself. That way you keep your sending history across device changes."
      }
    },
    {
      "@type": "Question",
      "name": "Do I have to keep paying the old rent during the process?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Until your landlord accepts the reduction or the conciliation authority decides, you continue paying the current rent. The new, lower rent is only owed from the effective date. Withholding on your own can trigger an immediate termination."
      }
    },
    {
      "@type": "Question",
      "name": "Can my landlord terminate my lease because I submitted a rent reduction request?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No, you are legally protected. A termination as a reaction to your rent reduction request is voidable under Art. 271a para. 1 lit. a of the Swiss Code of Obligations (CO) (so-called \"retaliatory termination\"). The burden of proof lies with the landlord: they must demonstrate that the termination is NOT motivated by your reduction request. In practice, landlords rarely succeed. The conciliation authority then declares such a termination invalid.  Additional protection: For three years from the conclusion of a conciliation or court proceeding, your landlord cannot ordinarily terminate the lease (Art. 271a para. 1 lit. e CO). A termination \"at an inopportune time\" (during or shortly after an ongoing proceeding) is also invalid (Art. 271a para. 1 lit. d CO).  A rent reduction request is a normal legal procedure. An adjustment of the rent to the current market level. Rent reductions are an everyday part of Swiss tenancy and not a confrontational act."
      }
    },
    {
      "@type": "Question",
      "name": "What do I do if I still receive a termination after the rent reduction request?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Act immediately. You only have 30 days from receipt of the termination to challenge it before the conciliation authority (Art. 273 CO). Step by step:  1. Note the date you received the termination. Keep the envelope with the postal stamp. 2. Save the termination letter + your letter history. In RentReducer under Settings → \"Export my data\", download the entire bundle. 3. Contact the tenants' association in your canton (mieterverband.ch / asloca.ch / asi-infoalloggio.ch). You receive free or low-cost help with the conciliation request. If not yet a member: join now, approximately CHF 60 to 100 per year, covers consulting and conciliation support. 4. Submit a conciliation request to the competent authority. Addresses of all cantonal authorities are on bwo.admin.ch. Reason: \"Challenge for retaliatory termination under Art. 271a CO\". 5. Request an extension (Art. 272 CO): up to four years extension of the lease for residential premises, even if the termination itself were valid. 6. Check your legal protection insurance. Many policies fully cover conciliation proceedings and extension claims.  RentReducer does not replace legal advice and does not act as your representation in the conciliation proceedings. In case of aggressive landlord reaction: tenants' association or lawyer."
      }
    },
    {
      "@type": "Question",
      "name": "Is my rent reduction request a conflict with my landlord?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. It is a legal right you have as a tenant if the reference interest rate has fallen since your last adjustment. No one \"wins\" or \"loses\". Landlords are required to respond in writing to your request within 30 days (Art. 270a CO).  For justified adjustments, they usually do so without discussion: the reduction costs them money in the short term, but it is legally clean and part of the normal tenancy. Many Swiss landlords and property managements process rent reductions as a matter of routine, without tenants having to actively request them.  In some cases (especially with small or conservative landlords), a reduction request may be perceived as uncomfortable. If the atmosphere of the lease changes noticeably or repairs are suddenly refused: the tenants' association in your canton helps you assess at low cost whether this is relevant and legally actionable."
      }
    },
    {
      "@type": "Question",
      "name": "Does RentReducer guarantee a successful reduction?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. RentReducer is a tool, not legal advice, and not a guarantee of a successful reduction. The calculation is conservative and based on Art. 270a Swiss Code of Obligations CO and Art. 13 Swiss Tenancy Ordinance OBLF, but it is non-binding. Your landlord is not obliged to accept your request without discussion. They can raise counter-arguments (inflation, cost increases, insufficient yield, local and neighbourhood customariness). The claim is assessed individually and, in case of dispute, by the conciliation authority. The makers of RentReducer assume no liability for the outcome of your proceedings. For binding information, contact the tenants' association or a qualified professional."
      }
    }
  ]
}
</script>

## Eligibility

<h3 id="when-am-i-entitled-to-a-rent-reduction">When am I entitled to a rent reduction?</h3>

As soon as the reference interest rate has dropped since your last rent adjustment or the start of your tenancy (Art. 270a CO). The reduction is not automatic. You have to actively request it from your landlord. <strong>RentReducer</strong> checks for you whether you currently have a claim and calculates the amount right after you enter your net rent and the last adjustment date.

<h3 id="how-does-the-app-calculate-my-claim">How does the app calculate my claim?</h3>

<strong>RentReducer</strong> follows the <strong>Swiss Tenancy Ordinance OBLF</strong> (Art. 13) and the <strong>Swiss Code of Obligations CO</strong> (Art. 269a). Three factors go into the calculation: (1) <strong>Reference rate drop</strong>, for every 0.25 % drop in the rate, rent decreases by 2.91 % (the conservative minimum per OBLF); for multiple steps, we apply the inverse of the cumulative increase. (2) <strong>General cost increase</strong>, 0.5 % per year since the last adjustment, which your landlord is allowed to offset against the reduction. (3) <strong>Inflation compensation</strong>, 40 % of the CPI (consumer price index) change since the last adjustment, also charged against the reduction. Your net claim is: reference rate drop minus cost increase minus inflation. If the result is negative, you have no claim, even if the rate dropped. For a binding calculation, contact the tenants' association.

<h3 id="where-do-the-reference-rate-and-inflation-data-come-from">Where do the reference rate and inflation data come from?</h3>

The reference rate is published by the <strong>Federal Office for Housing FOH</strong> (quarterly updates, sometimes unchanged carry-overs). The consumer price index (CPI) for inflation comes from the <strong>Swiss Federal Statistical Office FSO</strong> (monthly, released around the 6th of the following month). Both sources are legally binding. <strong>RentReducer</strong> fetches the current values on every start from the server (not from the app download), and we update them as soon as the FOH or FSO publishes a new value. If our data is ever out of date, you will see a discreet notice on the dashboard. You can check the raw data anytime at bwo.admin.ch and bfs.admin.ch.

<h3 id="why-does-the-app-sometimes-say-no-reduction-claim-even-though-the-reference-rate">Why does the app sometimes say "no reduction claim" even though the reference rate dropped?</h3>

For long-running leases (e.g. 10 years since the last adjustment), accumulated inflation (~1 % per year) plus cost increases (0.5 % per year) can be offset by your landlord against your reduction request. Result: rate drop + accumulated offsets = no net claim. <strong>RentReducer</strong> shows this case honestly so you don't send a letter your landlord could rightly reject. If you have doubts, or if the cost increase has already been offset by an earlier reduction, clarify with the tenants' association.

<h3 id="what-about-indexed-or-stepped-rental-contracts">What about indexed or stepped rental contracts?</h3>

For these contract types, a reduction based on the reference rate is <strong>excluded</strong> during the contract term. <strong>RentReducer</strong> does not detect the contract type automatically, you have to check briefly yourself.

<strong>How to identify your contract type:</strong>

- <strong>Standard rental contract</strong> (most common, about 90-95% of Swiss residential leases): rent is a fixed CHF amount per month, no index linkage and no pre-defined increases. Example: "Net rent CHF 1500 per month". → <strong>Reduction request under Art. 270a CO is possible.</strong>
- <strong>Indexed contract:</strong> rent is explicitly tied to the Swiss Consumer Price Index (CPI) and rises with inflation. Contract keywords: "indexed rent", "CPI linkage", "adjustment to the national index". Precondition: a lease with at least 5 years fixed duration (Art. 269b CO). → <strong>No reduction based on the reference rate.</strong>
- <strong>Stepped rent contract:</strong> rent increases according to a plan fixed in the contract, e.g., "Year 1 CHF 1500, Year 2 CHF 1550, Year 3 CHF 1600". Contract keywords: "stepped rent", "agreed rent steps". Precondition: minimum duration of 3 years (Art. 269c CO). → <strong>No reduction based on the reference rate.</strong>

If in doubt, the tenants' association in your canton (mieterverband.ch) can verify your contract.

<h3 id="can-i-claim-the-reduction-retroactively">Can I claim the reduction retroactively?</h3>

No. The reduction only takes effect from the next termination date after your request. Amounts overpaid in the past cannot be recovered. That's exactly why <strong>RentReducer</strong> offers the rate alert: we notify you as soon as the reference rate drops. So you never miss a reduction.

<h3 id="how-do-i-find-the-date-of-the-last-adjustment">How do I find the date of the last adjustment?</h3>

Check your rental contract and any later letters from your landlord (often on the official form). The last adjustment may be the start of the tenancy if there's been none. If unsure, choose "I'm not sure" in the wizard. <strong>RentReducer</strong> calculates conservatively with an estimate.


## Letter and dispatch

<h3 id="when-does-the-new-lower-rent-take-effect">When does the new, lower rent take effect?</h3>

The reduction takes effect on the next possible termination date after the contractual notice period (usually 3 months). If you file early enough, it applies to that date. <strong>RentReducer</strong> uses the 4 common Swiss quarter-ends by default (31.03 / 30.06 / 30.09 / 31.12) and automatically inserts the next possible date into the letter.

<h3 id="when-exactly-does-the-letter-have-to-reach-my-landlord">When exactly does the letter have to reach my landlord?</h3>

The letter must arrive before the notice period starts. Example: for a reduction from July 1st with a three-month notice period, the letter has to reach the landlord by the end of March. Send it by registered mail for proof of delivery. <strong>RentReducer</strong> inserts the next possible date automatically; you just decide when to mail it.

<h3 id="does-my-landlord-have-to-respond-to-the-letter">Does my landlord have to respond to the letter?</h3>

Yes. Your landlord has to respond in writing within 30 days. If they agree, the rent is adjusted. The letter generated by <strong>RentReducer</strong> states the 30-day deadline and the legal basis (Art. 270a Swiss Code of Obligations CO, Art. 13 Swiss Tenancy Ordinance OBLF), so your request is formally correct.

<h3 id="how-should-i-send-the-letter">How should I send the letter?</h3>

Registered mail is best. You get proof of delivery in case of dispute. <strong>RentReducer</strong> creates the PDF and you can send it directly from the app as a standard letter or as registered mail. Alternatively, download it as PDF or Word, print it and post it yourself. Always keep a copy for your records.

<h3 id="how-do-i-send-a-letter-directly-from-the-app">How do I send a letter directly from the app?</h3>

Create the letter in the wizard, open the preview and tap "Send letter" or "Send Registered". The first time, we ask for your signature (drawn once on the device). Then <strong>RentReducer</strong> hands the letter to the Swiss print service Pingen, which physically prints and posts it to your landlord. You receive a push notification the moment the letter is handed to Swiss Post, with registered mail, also on the day of delivery.

<h3 id="how-do-i-know-whether-my-letter-actually-arrived">How do I know whether my letter actually arrived?</h3>

As soon as <strong>Pingen</strong> (the Swiss letter-mailing service based in Zurich, pingen.com) hands your letter to Swiss Post, <strong>RentReducer</strong> sends you a push notification ("Letter on its way"). With <strong>registered mail</strong> (CHF 7.90 surcharge), you additionally receive a second push on the day of actual delivery ("Letter delivered on DD.MM."), and the Swiss Post tracking number appears in the letter view. A standard send by definition provides no proof of delivery (this is a Swiss postal-system trait, not a limitation of the app). If you need legal certainty about arrival, e.g. because you may go to conciliation, choose registered mail.

<h3 id="what-does-sending-cost">What does sending cost?</h3>

<strong>Standard letter delivery</strong> is included directly in the letter purchase (no surcharge). No extra cost, delivery typically within 2 business days. <strong>Registered</strong> costs an additional CHF 7.90 per letter (surcharge, not included), payable via App Store / Play Store. The price covers postage, proof-of-deposit and printing. At the post counter, a registered letter costs about CHF 5.70 plus your trip. Registered mail is legally recommended for reduction requests because it provides proof of delivery.

<h3 id="can-i-cancel-a-letter-that-s-already-been-sent">Can I cancel a letter that's already been sent?</h3>

Yes, <strong>within about 30 minutes of sending</strong>, as long as Pingen has not yet printed the letter. On the letter card in the dashboard a "Cancel" chip appears. Tap it, the letter is deleted at Pingen and goes back to draft in the app. You can then e.g. correct the recipient address and resend. If the letter is already printed, the app shows "Cancellation no longer possible", you then have to wait for the letter to come back (registered) or chalk it up as experience.

<h3 id="i-marked-the-letter-as-self-delivered-but-did-not-post-it-what-now">I marked the letter as self-delivered but did not post it. What now?</h3>

Tap the pencil icon on the letter card in the dashboard. The opening sheet shows a <strong>"Reset self-send"</strong> button. Confirm and the letter returns to draft status, the send date and any response status are removed. You can then resend it or download it as Word.

<h3 id="how-do-i-bring-back-an-archived-process">How do I bring back an archived process?</h3>

In the More tab under <strong>"Archive"</strong> you find all completed processes. Per process group there is a <strong>"Reactivate process"</strong> icon (circular arrow) next to the delete icon. Tap → confirmation dialog → the letters of that process re-appear in the active dashboard, the current status (accepted/partial/rejected) is preserved. Useful if you e.g. want to take a closed process to conciliation after all.

<h3 id="my-letter-came-back-undeliverable-what-now">My letter came back (undeliverable). What now?</h3>

In the dashboard a <strong>"Sending failed"</strong> hero appears with a hint about a possible address error. Tap "Check address" → you land directly in the landlord form. Correct the address, save, return to the letter and resend. <strong>Note:</strong> "undeliverable" only comes back for registered mail, because Swiss Post does not track standard letters. For legal proof of delivery we recommend the registered upgrade (+ CHF 7.90).

<h3 id="can-i-send-multiple-reminder-letters">Can I send multiple reminder letters?</h3>

Yes. If your landlord remains silent despite the first reminder, you can send a <strong>second (or third) reminder letter</strong>. Tap the reminder CTA as usual, the app shows a dialog "Already sent on DD.MM., resend?" and you confirm the purchase (CHF 6.90 per follow-up letter). Often legally meaningful as a last escalation before the conciliation petition, because multiple reminders document the process. Same logic for the documents request.

<h3 id="does-the-conciliation-authority-accept-my-letter-from-rentreducer-or-do-i-need-a">Does the conciliation authority accept my letter from RentReducer, or do I need a cantonal form?</h3>

The conciliation letter generated by <strong>RentReducer</strong> complies with <strong>Art. 202 para. 2 CPC</strong>: it contains the designation of the opposing party, the legal claim and the subject of the dispute, as well as your signature. It must therefore be accepted by <strong>all Swiss conciliation authorities</strong> in tenancy matters. There is no federal requirement to use a cantonal form.

<strong>Some cantons (e.g., Zurich, Berne) additionally offer their own conciliation forms</strong> to speed up internal processing. These forms are a recommendation, not a requirement. If your conciliation authority asks for a form: you can submit it later; your initial filing remains valid within the deadline (the date of the RentReducer letter counts for the 30-day deadline under Art. 273 CO).

If you prefer the cantonal form: contact the competent conciliation authority for your residence. Addresses are listed on bwo.admin.ch under "Schlichtungsbehörden / Conciliation authorities". In this case, download the conciliation letter from <strong>RentReducer</strong> as a Word file and transfer the calculations and attachment list into the form.

<h3 id="how-do-i-track-the-conciliation-hearing-in-the-app">How do I track the conciliation hearing in the app?</h3>

Once you have sent the conciliation petition letter, a <strong>"Proceedings timeline"</strong> card appears under the letter with three phases. (1) <strong>Summons received</strong>: tap and enter the date you received the summons from the conciliation authority. (2) <strong>Hearing date</strong>: the date of the hearing itself. (3) <strong>Outcome</strong>: after the hearing pick "Agreement reached", "Settlement concluded" or "Case goes to court". You've now documented the proceedings in the app, parallel to your official files at the authority.

<h3 id="can-i-edit-the-letter-text">Can I edit the letter text?</h3>

Yes, download the letter as Word (preview → download icon in the top right → Word). Important: <strong>as soon as you change the text in the Word file, you can no longer send the letter via RentReducer</strong>. You then need to print it and post it yourself. In-app sending only works with the original app text because the letter is handed to the print service before you could make any changes.

<h3 id="is-my-in-app-signature-legally-valid">Is my in-app signature legally valid?</h3>

Yes, for all letters in <strong>RentReducer</strong> it is sufficient. Swiss rental law (art. 270a CO) does not prescribe any particular form for reduction requests or follow-up letters. Your finger-drawn signature meets practical standards and is accepted by landlords. The signature is stored only locally on your device and transmitted to the print service only at send time.

<h3 id="is-a-finger-drawn-signature-on-the-smartphone-legally-valid">Is a finger-drawn signature on the smartphone legally valid?</h3>

The rent reduction request is <strong>form-free under Art. 270a CO</strong>: no written form, no handwritten signature required. The finger-drawn signature in <strong>RentReducer</strong> therefore goes far beyond what is legally needed and is more than sufficient. The Federal Supreme Court confirmed in <strong>BGE 144 III 81</strong> that a simple electronic signature is equivalent to a handwritten one for form-free legal transactions (see also Art. 13/14 CO on simple written form as the default for form-bound transactions). If the matter goes to a conciliation procedure, <strong>RentReducer</strong> already provides the necessary identification through your recorded personal details (name, address).

<h3 id="do-all-tenants-need-to-sign">Do all tenants need to sign?</h3>

Legally no, Swiss rental law prescribes no form. But it is strongly recommended in practice: landlords may refuse a request made by one person without the consent of the others. With multiple contract parties, <strong>RentReducer</strong> offers two paths: sign together on the device (the wizard passes the device between the parties) and send via the app, or download the letter, have it signed on paper and post it yourself.


## Follow-up letters

<h3 id="does-rentreducer-offer-follow-up-letters-too">Does RentReducer offer follow-up letters too?</h3>

Yes. Under <strong>"Your letters"</strong> on the dashboard you'll find, alongside the main reduction request, three follow-up letters: "Reminder letter" (if your landlord doesn't respond at all, happens often), "Request explanation and evidence" (if they refuse citing cost flat rates, local/district customariness or yield) and "Apply for conciliation" (if silence continues or the answer is insufficient). All letters come pre-filled with your data, available as PDF and editable Word document.

<h3 id="my-landlord-doesn-t-respond-at-all-what-now">My landlord doesn't respond at all, what now?</h3>

Very common. Many (especially smaller) landlords simply don't react to a reduction request. After 30 days of silence you can legally go straight to the conciliation authority. But often it pays off to first send a friendly reminder with a final deadline. Under <strong>"Your letters"</strong> you'll find the "Reminder letter" follow-up for this: it confirms the date of your original letter, sets a new 14-day deadline, and announces that you'll file with the authority otherwise. Often this alone prompts a response and avoids escalation.

<h3 id="what-can-my-landlord-offset-against-my-claim">What can my landlord offset against my claim?</h3>

Two factors: 40 % of accumulated inflation and general cost increases (maintenance, administration, fees, property tax, insurance). The Federal Supreme Court requires landlords to prove cost increases via a comparative calculation. In practice, many conciliation authorities accept flat-rate offsets if tenants don't object. If you do challenge the flat rate, your landlord must document actual costs using 3- or 5-year averages. If your landlord argues with such a flat rate: under <strong>"Your letters"</strong> you'll find the "Request explanation and evidence" (CHF 6.90) follow-up to demand the evidence. <strong>RentReducer</strong> deliberately calculates without these deductions. Your net claim may end up lower.

<h3 id="what-can-i-do-if-my-request-is-refused">What can I do if my request is refused?</h3>

You can file a petition with the conciliation authority of your district within 30 days of receiving the response. If your landlord doesn't reply or replies late, you have 60 days from the original letter's dispatch. The procedure is free. Common (often untenable) refusal reasons: insufficient yield, lack of local or neighbourhood customariness, excessive flat-rate cost offsets. Under <strong>"Your letters"</strong> you can create the appropriate follow-up letters: "Request explanation and evidence" for a refusal citing one of these reasons, "Apply for conciliation" to file with the authority. If in doubt, the tenants' association can help. <strong>RentReducer</strong> does not handle the conciliation itself.

<h3 id="does-rentreducer-remind-me-if-nothing-happens">Does RentReducer remind me if nothing happens?</h3>

Yes. After you send the letter, <strong>RentReducer</strong> checks back automatically after 14, 30 and 60 days if your landlord did not respond. With one tap you set the status (accepted / partial / rejected / no response yet) and the app suggests the right follow-up letter directly. You do not have to write anything down in your calendar. We remind you until you say your case is done.


## App and data

<h3 id="what-does-the-app-store-on-my-device-and-is-my-data-safe">What does the app store on my device, and is my data safe?</h3>

Everything you enter, tenant, landlord, lease, letters and your signature, stays <strong>locally on your device</strong>, in an encrypted database (AES-256). The key lives in the Keychain (iOS) or Keystore (Android) and never leaves the device. When you send a letter, only the finished PDF is handed to Pingen (Swiss print service, signed AVV). <strong>No account</strong>, no cloud sync, no advertising IDs. You can wipe everything anytime via Settings → Privacy → "Erase all my data".

<h3 id="how-much-does-rentreducer-cost">How much does RentReducer cost?</h3>

<strong>You pay per letter, everything included, one tap.</strong> Checking your claim + the rate alert are free. To send the reduction letter you pay once between <strong>CHF 9.90 and 29.90</strong> per letter. The price depends on your monthly savings (about 30 % of the first month's savings, floor 9.90, ceiling 29.90). Included: letter generation, printing, automatic letter dispatch via <strong>Pingen</strong> (Swiss letter-mailing service, pingen.com), push notification the moment the letter is on its way, automatic reminders after 14/30/60 days if no answer comes. No subscription, no recurring payments. <strong>Registered mail as an upgrade</strong>: + CHF 7.90, and you get a second push on the day of delivery. <strong>Follow-up letters</strong>: CHF 6.90 each if your landlord does not respond. Reminder and document-request go out automatically via Pingen. The <strong>conciliation announcement</strong> is also sent directly by <strong>RentReducer</strong> as of v1.0.x: you take a photo of the lease (mandatory attachment) and any further correspondence, the app auto-attaches copies of your previous letters, and the whole packet goes by registered mail (CHF 7.90 surcharge) to the conciliation authority. Alternatively you can still download the letter as Word and post it yourself.

<h3 id="do-i-have-to-pay-monthly-or-yearly">Do I have to pay monthly or yearly?</h3>

No. <strong>RentReducer</strong> is not a subscription. You pay once per letter. And only when you actually want to create one. No recurring access to your account, no cancellation to handle. If you become eligible again in a few years (a new drop of the reference rate), you can buy another letter. Again per letter, without anything running in the background.

<h3 id="what-if-i-install-rentreducer-on-a-new-device">What if I install RentReducer on a new device?</h3>

If you reinstalled RentReducer or switched devices, you can recover your purchases via <strong>Settings → Restore purchases</strong>. Apple and Google provide the list of your prior purchases. <strong>RentReducer</strong> records them locally again.

<h3 id="can-i-cancel-a-purchase-or-get-a-refund">Can I cancel a purchase or get a refund?</h3>

Letters are digital services delivered immediately: after you tap "Send", the letter goes to the printing service and is physically produced. A cancellation after sending is therefore not possible. If you paid but haven't sent (e.g. you closed the app before sending), you can request a refund through your App Store within 14 days. <strong>iOS:</strong> reportaproblem.apple.com → RentReducer → purchase → "Report a Problem". <strong>Android:</strong> play.google.com → Orders → RentReducer → "Request a refund". Apple and Google decide on the refund. <strong>RentReducer</strong> doesn't handle payments directly and cannot cancel a purchase on its own.

<h3 id="what-happens-to-my-data-if-i-delete-and-reinstall-the-app">What happens to my data if I delete and reinstall the app?</h3>

Your letters, lease details, and signature are <strong>AES-256 encrypted and stored only on your device</strong>. The key lives in the iOS Keychain or Android Keystore and is tied to the installation. If you delete <strong>RentReducer</strong>, the key is deleted with it and the encrypted database becomes unreadable, even for the app makers. This is intentional: no cloud, no account, no trail. After reinstalling you can only restore your <strong>purchases</strong> (Apple/Google); your letters and inputs must be re-entered. Tip: download important letters as <strong>Word or PDF</strong> and back them up to your cloud storage or email them to yourself. That way you keep your sending history across device changes.

<h3 id="do-i-have-to-keep-paying-the-old-rent-during-the-process">Do I have to keep paying the old rent during the process?</h3>

Yes. Until your landlord accepts the reduction or the conciliation authority decides, you continue paying the current rent. The new, lower rent is only owed from the effective date. Withholding on your own can trigger an immediate termination.


## Legal notice

<h3 id="can-my-landlord-terminate-my-lease-because-i-submitted-a-rent-reduction-request">Can my landlord terminate my lease because I submitted a rent reduction request?</h3>

No, you are legally protected. A termination as a reaction to your rent reduction request is voidable under <strong>Art. 271a para. 1 lit. a of the Swiss Code of Obligations (CO)</strong> (so-called "retaliatory termination"). The burden of proof lies with the landlord: they must demonstrate that the termination is NOT motivated by your reduction request. In practice, landlords rarely succeed. The conciliation authority then declares such a termination invalid.

<strong>Additional protection:</strong> For <strong>three years</strong> from the conclusion of a conciliation or court proceeding, your landlord cannot ordinarily terminate the lease (Art. 271a para. 1 lit. e CO). A termination "at an inopportune time" (during or shortly after an ongoing proceeding) is also invalid (Art. 271a para. 1 lit. d CO).

A rent reduction request is a normal legal procedure. An adjustment of the rent to the current market level. Rent reductions are an everyday part of Swiss tenancy and not a confrontational act.

<h3 id="what-do-i-do-if-i-still-receive-a-termination-after-the-rent-reduction-request">What do I do if I still receive a termination after the rent reduction request?</h3>

Act immediately. You only have <strong>30 days</strong> from receipt of the termination to challenge it before the conciliation authority (Art. 273 CO). Step by step:

1. <strong>Note the date</strong> you received the termination. Keep the envelope with the postal stamp.
2. <strong>Save the termination letter + your letter history</strong>. In <strong>RentReducer</strong> under Settings → "Export my data", download the entire bundle.
3. <strong>Contact the tenants' association</strong> in your canton (mieterverband.ch / asloca.ch / asi-infoalloggio.ch). You receive free or low-cost help with the conciliation request. If not yet a member: join now, approximately CHF 60 to 100 per year, covers consulting and conciliation support.
4. <strong>Submit a conciliation request</strong> to the competent authority. Addresses of all cantonal authorities are on bwo.admin.ch. Reason: "Challenge for retaliatory termination under Art. 271a CO".
5. <strong>Request an extension</strong> (Art. 272 CO): up to <strong>four years extension</strong> of the lease for residential premises, even if the termination itself were valid.
6. <strong>Check your legal protection insurance</strong>. Many policies fully cover conciliation proceedings and extension claims.

<strong>RentReducer does not replace legal advice</strong> and does not act as your representation in the conciliation proceedings. In case of aggressive landlord reaction: tenants' association or lawyer.

<h3 id="is-my-rent-reduction-request-a-conflict-with-my-landlord">Is my rent reduction request a conflict with my landlord?</h3>

No. It is a legal right you have as a tenant if the reference interest rate has fallen since your last adjustment. No one "wins" or "loses". Landlords are required to respond in writing to your request within 30 days (Art. 270a CO).

For justified adjustments, they usually do so without discussion: the reduction costs them money in the short term, but it is legally clean and part of the normal tenancy. Many Swiss landlords and property managements process rent reductions as a matter of routine, without tenants having to actively request them.

In some cases (especially with small or conservative landlords), a reduction request may be perceived as uncomfortable. If the atmosphere of the lease changes noticeably or repairs are suddenly refused: the tenants' association in your canton helps you assess at low cost whether this is relevant and legally actionable.

<h3 id="does-rentreducer-guarantee-a-successful-reduction">Does RentReducer guarantee a successful reduction?</h3>

No. <strong>RentReducer</strong> is a tool, not legal advice, and not a guarantee of a successful reduction. The calculation is conservative and based on Art. 270a Swiss Code of Obligations CO and Art. 13 Swiss Tenancy Ordinance OBLF, but it is non-binding. Your landlord is not obliged to accept your request without discussion. They can raise counter-arguments (inflation, cost increases, insufficient yield, local and neighbourhood customariness). The claim is assessed individually and, in case of dispute, by the conciliation authority. The makers of <strong>RentReducer</strong> assume no liability for the outcome of your proceedings. For binding information, contact the tenants' association or a qualified professional.

