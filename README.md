# JVM School – Pitch Kit

JVM Senior Secondary School (Jhotwara, Jaipur) ke owner ko pitch karne ke liye 3 cheezein.
Sab plain HTML files hain: koi install nahi, double-click karke browser mein khul jaati hain (laptop ya phone dono par).

| File | Kya hai | Kaise use karein |
|---|---|---|
| `pitch-deck.html` | 11 slides ka English proposal (16 automation services ki list ke saath) | ◀ ▶ arrow keys / swipe se slide badlo. 🖨️ button → "Save as PDF" se PDF bana lo |
| `demo-website/index.html` | School ki nayi website ka 3D demo (poora English mein) | 3D hero (Three.js), tilt/flip cards, 3D gallery, parent app mockup, 16 automation services ka section, AI chat assistant (🤖 button), online fee check (try `A101`, `A102`, `A103`), admission form, WhatsApp button, Google Map |
| `fee-system/index.html` | Fee Manager prototype | Dashboard, students, payment record, auto receipt, WhatsApp reminder, CSV export |

## Meeting mein demo ka order
1. **Pitch deck** dikhao (5 min). Slide 10 par apni pricing bhar lo (`₹____` waali jagah).
2. **Fee Manager** kholo → Students → kisi bachche par **📲 Remind** dabao → WhatsApp par Hindi reminder khulega.
   Phir **₹ Pay** → payment save → receipt bani → **Send on WhatsApp**.
3. **Website** dikhao: mobile par kholo, admission form bharo → school ke WhatsApp par enquiry jaati hai.

## Demo se pehle badalna
- `fee-system` → **Settings** mein school ka asli UPI ID daalo.
- `demo-website` mein Unsplash ki sample photos hain; school ki asli photos se badalni hain.
- "Nursery–12" aur facilities (labs, transport) school se confirm karke theek karo.
- Website par testimonials, notices, school timings (chat assistant mein) aur streams (Science/Commerce/Arts) sample hain. School se confirm karo.
- Pitch deck slide 11 par apna naam / phone bharo.

## Demo aur real version mein farq
- Demo mein data sirf usi browser mein save hota hai (localStorage). Real version mein database (Supabase/Firebase) hoga.
- Demo mein reminder ek-ek click se WhatsApp par khulta hai. Real version mein WhatsApp Business API (Interakt / AiSensy / WATI) se sab parents ko due date par apne aap jaayega.
- Website ka "Pay" button demo hai. Real version mein Razorpay/UPI gateway lagega, aur payment hote hi receipt auto-send hogi.
