![Two ID cards with the same name, birth date and SSN. The left is a dashed copy with no photo. The right is solid, with a photo and a verified seal.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/00-hero.png)

*Both cards carry the same facts. Only one of them is me. (Sample data.)*

When it comes to protecting your identity, the typical advice goes like this. Guard your Social Security number. Shred your mail. Check your credit report. Watch for charges you don't recognize.

This is good advice, and I follow it. But it's all defense, and it often isn't enough. In a single year, about 1 in 11 Americans aged 16 and older had their identity stolen.

Here's a puzzle. Your bank account number is printed on every check you've ever written. It isn't a secret. Yet nobody can empty your account just by knowing it.

Your Social Security number is guarded far more carefully. Yet a thief who knows it, plus your name and birth date, can open a credit card as you.

![Two objects side by side. Left: a paper check with a sample account number printed along the bottom. It is printed on every check you write, and it can't empty your account. Right: a Social Security card showing a sample number ending in 4821. It is guarded carefully, yet it opens a credit card in your name.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/01-puzzle.png)

*Sample data.*

Why does one number work like a key, when the other doesn't?

The answer explains how identity theft works. It explains why phishing and AI are making it worse. And it points to a fix that may sound backward: hand the proof of who you are to a trusted specialist, then put it to work.

You already do this with money. You trust a bank to keep it safe, and to let you use it. This post asks whether identity can work the same way.

## Part 1. The puzzle

### What does it take to prove you're you?

Your identity is a set of facts about one real person. Your name, birth date, address, and Social Security number are the usual ones.

When you open a bank account, check in at a doctor's office, or renew a license at the DMV, you make a claim: "I am this person." The business on the other side has to decide whether to believe you. Some businesses check for themselves. Others hand the job to an identity provider, a company that specializes in it.

A good check answers two questions.

**1. Who are you claiming to be?** You give your name, birth date, and Social Security number, and maybe an ID. The checker confirms the ID is genuine and the details match a real person in trusted records. This is the facts check.

**2. Are you really that person?** The checker confirms the one applying is the one those facts belong to. Matching your face to the photo on your ID is one way. A code sent to a phone already tied to you is another. So is holding something only you have, like a card and PIN. This is the person check.

![A claim card reading I am Jane Q. Public passes through two gates in order, then is trusted. Gate 1 asks who are you claiming to be: a facts check that the ID is genuine and the details match records. Gate 2 asks are you really that person: a person check by face, phone code, or something only you hold.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/02-two-checks.png)

That solves the puzzle. Your bank runs both checks. The account number only answers the first question: which account. Your card and PIN answer the second. Many identity checks lean on the first. When the facts match and nothing looks odd, knowing the facts passes as proof of being the person.

Identity experts call these two checks validation and verification. The addendum at the end has the details. This post sticks to the plain names.

### So what does a thief need?

Just your facts, and big companies have already leaked them for hundreds of millions of people. Picture someone applying for a credit card in your name. They type in your name, birth date, and Social Security number.

The bank checks that the details match a real person. They do, because they're your real facts. The facts check passes. Nothing else looks odd, so the bank never runs the person check. The card is approved.

![One lane. Someone types in your name, birth date, and SSN. The facts check asks do the details match a real person, and passes because they are your real facts. The person check is drawn dashed and greyed, marked skipped. The result, in red, is approved for the thief.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/03-attack.png)

The bank confirmed *which* person was being claimed. It never confirmed *who* was making the claim.

> **Knowing facts about me should not be enough to *act as me*.**

That raises two questions. How often does this actually happen? And by now, don't businesses check more than facts?

## Part 2. The problem

### How often does this happen?

First, what counts. The FTC defines identity theft as someone using your personal or financial information without your permission. Notice the word *using*. When your data leaks, that's exposure. Theft is when someone puts that data to work as you.

It happens a lot. In a 2021 federal survey, about 23.9 million U.S. residents had their identity stolen in the past 12 months. The FTC received more than 1.1 million identity theft reports in 2024. Those are reports, not a count of unique victims. Credit card misuse was the largest named type, at about 4 in 10 reports.

It shows up in three common forms:

- **A new account in your name.** Someone opens a credit card or loan using your facts. That's the example above.
- **A takeover of an account you have.** Someone gets in, often through a password reset or account recovery.
- **A person who doesn't exist.** Someone stitches pieces of personal information into a made-up identity. This is called synthetic identity fraud.

You might think careful people are safe. But only about 1 in 5 victims know how their information got out. For those who do, a lot of it happened where they had no say.

![Five person icons, one filled: 1 in 5 victims know how their information was obtained. Bars: online 37.5%, in-person purchase 17.6%, company or employer files 16.3%, mail, wallet, home or car 11.3%, other 17.2%.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/04-where-stolen-info-came-from.png)

*Source: Bureau of Justice Statistics, Victims of Identity Theft, 2021, Table 4. Shares don't total 100% due to rounding.*

| How the information was obtained | Share |
| --- | --- |
| Online (scam emails and calls, online shopping, device access) | 37.5% |
| In-person purchase (skimmers, card readers) | 17.6% |
| Company or employer files | 16.3% |
| Mail, wallet, home, or car | 11.3% |
| Other | 17.2% |

The biggest group, almost 4 in 10, said it happened online, through scam emails, scam calls, or online shopping. About 1 in 6 traced it to files a company or employer kept. About 1 in 6 more traced it to an in-person transaction, such as a card skimmer. You can shred every letter and still lose your data this way.

The breaches keep coming. The Identity Theft Resource Center counted 3,322 publicly reported data compromises in the U.S. in 2025. That's up 79% from 2021. It counts incidents, not the people affected.

![Line chart. Data compromises rose from 1,859 in 2021 and 1,798 in 2022 to 3,202 in 2023, 3,152 in 2024 and 3,322 in 2025.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/05-compromises-per-year.png)

*Source: ITRC 2025 Annual Data Breach Report, Figure 1. Counts publicly reported incidents, not their size or the people affected.*

| Year | Compromises |
| --- | --- |
| 2021 | 1,859 |
| 2022 | 1,798 |
| 2023 | 3,202 |
| 2024 | 3,152 |
| 2025 | 3,322 |

Some of them were enormous. And the leaks came from places people trusted: health insurers, a credit bureau, a hotel chain, a bank, a phone company, even the federal government's personnel office.

![Some of the biggest breaches: Yahoo 2013, 3 billion accounts; Marriott 2014, 339 million guest records; OPM 2015, 21.5 million people; Anthem 2015, 79 million people; Equifax 2017, 147 million people; Capital One 2019, 100 million people; AT&T 2024, 73 million account holders.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/06-biggest-breaches.png)

*Sources: FTC, HHS, OPM, SEC filings, company statements. Counts use each source's own unit.*

| Year | Company | Affected | Exposed |
| --- | --- | --- | --- |
| 2013 | Yahoo | 3 billion accounts | Account details; not clear-text passwords |
| 2014 | Marriott / Starwood | 339 million guest records | Includes 5.25 million unencrypted passport numbers |
| 2015 | U.S. Office of Personnel Management | 21.5 million people | SSNs; fingerprints for 5.6 million |
| 2015 | Anthem | 79 million people | Health plan records, SSNs, birth dates |
| 2017 | Equifax | 147 million people | Names and birth dates; 145.5 million SSNs |
| 2019 | Capital One | 100 million people | Credit applications; about 140,000 SSNs |
| 2024 | AT&T | 73 million account holders | SSNs, in data from 2019 or earlier |

So assume your facts are already out there. Which brings back the second question.

### Don't businesses check more than facts by now?

Many do, at least at the front door. But to see why facts still matter, start with how they became keys.

The Social Security number was never meant to be a key. It was created in 1936 to track workers' earnings. From 1946 to 1972, the cards even said "Not For Identification."

But the number was unique, and it was on everyone's paperwork. Lenders, employers, and health plans started using it to tell people apart. Then they started treating anyone who knew it as its owner. A label became a password.

In person, the second check came for free. A clerk looked at your ID, then looked at you. When forms moved online, the facts check came along and the face check got left behind.

Businesses patched the gap with quiz questions, like "which street did you live on in 2009?" Those questions often draw on credit and public records, so a thief can often find the answers too. In 2015, thieves used stolen data to get through the IRS's own quiz, and an estimated 724,000 tax accounts were potentially accessed. Then in 2017, Equifax, one of the three big credit bureaus, leaked the names, birth dates, and Social Security numbers of about 147 million people. Federal identity guidelines now say those quizzes must not be used to confirm who someone is.

![Timeline of how the Social Security number went from a worker-tracking label to a password: 1936 created, 1946 to 1972 cards say Not For Identification, 2015 IRS quiz bypassed, 2017 Equifax breach.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/07-timeline.png)

Since then, big banks and lenders have added layers. They look at your device, your phone number's history, and patterns across many applications. Bank regulators now say reliable checks "generally do not depend solely on knowledge-based questions." Federal identity guidelines go further, but they only bind federal agencies. Everyone else may choose to follow them.

Even so, thieves still get in four common ways.

- **When nothing looks odd.** Most checks are risk-based. If your facts match and the signals look normal, you pass without a stronger check. Stolen facts are real, so they look normal. Fraud rings also build fake identities slowly. The Federal Reserve describes how they build up a fake identity's credit, then "bust out" with big purchases and disappear.
- **At the side doors.** Call centers and account recovery may still fall back on your birth date or part of your Social Security number. And your email is a master key. The FTC warns that whoever controls it can reset the passwords on your other accounts.
- **With old passwords.** Breaches leak passwords too, and many people reuse them. So thieves try leaked pairs on other sites. This is called credential stuffing. In 2022, New York's attorney general found more than 1.1 million accounts at 17 companies hit this way.
- **When you hand them over.** Phishing tricks you into typing your password, and the code from your phone, into a fake site. The fake site passes them to the real one as you type. CISA, the federal cybersecurity agency, says one-time codes are "vulnerable to phishing attacks." Phishing was the most common complaint to the FBI's cybercrime center in 2024, with 193,407 reports.

And every business runs its own checks, its own way. A thief only needs the weakest one.

So why do weak checks survive? Partly because the business doesn't carry the whole cost. Every extra check adds friction, and some real customers give up. When fraud gets through, much of the cost lands on the victim instead. For a stolen credit card, the FTC says the most you might owe is $50. Identity theft has no such cap. The victim makes the calls, files the disputes, and fixes the credit reports. In the 2021 federal survey, about 1 in 10 victims who got their problems resolved spent a month or more doing it.

So why not make every business check the person with biometrics, like matching your face to your ID photo? Many now do. But that check has limits of its own, and AI just added a big one.

### Why not just use biometrics?

Biometrics means checking your body: your face, your fingerprint, or your voice. Remote checks lean on the face, since that's what a phone camera can capture.

That only became practical recently. In 2011, about 35% of U.S. adults had a smartphone. By 2025, 91% did. Phones got fingerprint unlock in 2013 and face unlock in 2017. Before that, most people had no good camera at hand for a remote face check.

Biometrics have other limits too. Accuracy can vary across people. A 2019 NIST study found many face matching algorithms made far more false matches for some demographic groups, and the gap varied widely from one algorithm to the next. Several states, including Illinois, Texas, and Washington, have laws on collecting biometrics. Not everyone has a phone with a good camera. And a face isn't a secret. NIST puts it plainly: biometrics "do not constitute secrets," and they "can often be obtained online." Fingerprints leak too. In 2015, the federal Office of Personnel Management lost the fingerprints of 5.6 million people. Unlike a password, those can't be changed.

Then came AI. In December 2024, the FBI warned that criminals use AI to make scams more believable. It named cloned voices of family members, fake video calls, fake IDs, and fake social media profiles.

The warnings kept coming. In May 2025, it warned about AI voice messages posing as senior U.S. officials. In July 2026, it warned about deepfake videos of FBI leaders, aimed at people who had already been scammed once. Banks see it too. In November 2024, FinCEN, a Treasury bureau, said more suspicious activity reports from banks described deepfakes. Many involved fake ID documents used to get past identity checks. One red flag on its list: a customer using a third-party webcam plugin during a live check.

The fakes can be cheap. In 2024, a reporter bought an AI-made fake ID image for $15. In the reporter's own test, it got through a crypto exchange's ID check. That same year, a finance worker in Hong Kong sent about $25 million after a video call. Every other person on the call was a deepfake.

![Four AI fakes, each paired with a test that beats it: cloned voice, deepfake video call, AI-made fake ID, and injected video.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/08-ai-fakes.png)

Look at what these tricks beat. A cloned voice beats "it sounds like her." A fake ID image beats "it looks real." They fool the human eye and weak software. A real test has to catch what the eye misses.

And they hit both checks. A fake ID image attacks the facts check. A deepfake face attacks the person check.

The checks are getting stronger. Good providers now test whether a camera feed comes from a real camera, not software pretending to be one. At home, the FBI suggests a simpler test: a secret word your family agrees on. Keeping these checks easy for real people and hard for fakes is its own problem. And every check that relies on how something looks or sounds is now in an arms race.

> **The problem in four lines**
>
> 1. Facts still open too many doors.
> 2. Your facts are already out there, leaked by companies you trusted.
> 3. Old passwords leak, and phishing steals your codes as you type them.
> 4. AI makes faking your face, voice, and ID cheap.

And every business is fighting all of this alone. Is there a better way?

## Part 3. The fix: a trusted identity provider

### Who should do the checking?

Every business runs its own checks. Each one has to keep up with phishing, deepfakes, and fake documents on its own. A thief only needs to beat the weakest one.

Money doesn't work that way. Stores don't each guard your cash. A bank does, and you can use that money almost anywhere. The bank is a specialist, and outsiders check its work.

Identity can work the same way. That's my position:

> **Let a trusted identity provider you choose protect your identity, so you can *use it* safely.**

A good provider does the hard check once, with the best defenses. It gives you a key that phishing and AI can't steal. It guards the side doors. And it vouches for you, so each business doesn't start from scratch.

How does that work? Start with what a thief can't fake.

### What can't a thief fake?

Two things: a secret they never had, and a history they never lived. Start with the secret. Think back to your bank card. A thief can photograph it, but a photo won't work at an ATM without your PIN. A copy of how something looks isn't the thing.

The digital version is a cryptographic key stored on your device. A passkey is one. It unlocks with your fingerprint, face, or PIN, and the key itself never leaves your device. There's no password to reuse or leak, either. That biometric check happens on your own phone. Nothing gets sent for a deepfake to imitate. The key also works only with the real website it was made for, so you can't be tricked into using it on a fake one. CISA calls this kind of sign-in "the gold standard." A thief can phish a code. They can't phish a key that won't work on their site, and AI can't sign in with a key it doesn't have.

The second thing is time. A deepfake takes minutes to make. A phone number you've had for ten years took ten years. The same goes for a long-held email address, a home address, or a bank account. So good checks also ask how long these facts have been tied to you. Has this phone number belonged to this person for years? Did its SIM card just move to a new phone?

This matters because of SIM swapping. A thief talks your carrier into moving your number to their phone, then receives your codes. Leaked carrier data can make that easier. In 2024, AT&T said data on about 73 million current and former account holders, including Social Security numbers, had leaked. The FBI got 1,611 SIM swap complaints in 2021, with losses over $68 million. Since 2023, the FCC has required carriers to check who's asking before moving a number, and to tell you when someone tries.

A brand-new number doesn't prove fraud. Real people switch numbers all the time. But it's a reason to ask for more proof. Federal guidelines tell services to watch for signs like a SIM change or a ported number before sending a code to a phone.

![Two columns. Left, in red, three things AI can copy, each labeled can be faked: a face, a voice waveform, and an ID image. Right, in green, two things AI can't fake. A phone holding a key, labeled a key on your device that never leaves it and works only with the real site. And a calendar, labeled years of history, such as a phone number you've had for a decade, since time can't be faked in minutes.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/10-copy-vs-key.png)

But a key only proves you hold that key. It doesn't say who you are. So how does a business know the key belongs to the right person?

### How do you tie the key to the right person?

In three steps: prove, protect, present.

**1. Prove who you are, once.** A provider runs both checks carefully. It confirms your ID is genuine and its details match records. Then it matches your face to the photo, and checks that the face is live and the camera is real. It also looks at how long your phone number and other details have been tied to you.

**2. Protect the way back in.** The provider ties that proof to your key. Each time you come back, you show you still hold it. No more face checks, no more quizzes.

**3. Present the proof elsewhere.** When another business needs to know who you are, your provider vouches for you. You sign in with your key. The business gets a confirmed answer, and you skip step one.

![Three steps. Step 1, prove, once: both checks, done carefully. Step 2, protect, at every sign-in: show you still hold your key, shown as several small sign-in marks. Step 3, present, in many places: your provider vouches for you, fanning out to three businesses, a bank, a clinic, and a benefits office.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/11-three-steps.png)

Now replay the credit card application. This time the bank asks your provider to confirm it's you. The thief has your facts, but not your key. The application stops.

![A credit card application replayed. Someone types in your name, birth date, and SSN. The bank asks your provider: is this really Jane? The thief is asked to show a key and has none, only facts. The result is stopped, in green.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/12-stopped.png)

The check AI attacks happens once, with strong defenses. Every check after that uses a key AI can't copy.

There's a catch, though. Whoever proves first gets the key. What stops a thief from proving first, as you?

### What stops a thief from proving first?

You do, by going first. If you never set up an account, a thief with your facts and a good fake can try to set one up in your name. So claim your identity before someone else does.

Some government services already recommend this. The Social Security Administration says creating your own online account takes "away the risk of someone else trying to create one in your name." The IRS offers an Identity Protection PIN to anyone who can verify their identity. It stops others from filing a tax return with your Social Security number. A free credit freeze at each of the three credit bureaus means nobody, including you, can open new credit in your name until you lift it. That blocks the credit card attack from Part 1. Turning on passkeys for your important accounts protects the way back in.

Remember the fix that sounded backward? This is it. Handing your proof to a provider you trust, and using it on purpose, closes doors before a thief can open them.

But claiming your identity means handing proof of it to someone. Who are these providers?

### Who are the identity providers?

There are a few kinds, and you may already use one.

**Government.** Login.gov is run by GSA, the federal agency that handles shared services. More than 50 federal and state agencies use it, and it can verify your identity as well as sign you in.

**Private companies.** CLEAR and ID.me verify your identity once, then let you reuse it at places that accept them.

**Your state.** A growing number of states issue mobile driver's licenses. You can keep them in a phone wallet, and TSA accepts them at many airport checkpoints.

![Three kinds of identity providers: government, private companies, and your state.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/13-providers.png)

*Examples, not a ranking.*

Some of these are already the way in to services you use. Social Security's online account accepts Login.gov or ID.me. The IRS uses ID.me for sign-in. So claiming your identity at those two places also claims it with a provider.

One common mix-up: "Sign in with Apple" or "Sign in with Google" isn't the same thing. Those, and passkeys alone, prove the same account holder is back. They don't prove who you are.

So how do you tell a strong provider from a weak one?

### What makes a provider worth trusting?

Think about what you expect from a bank. Expect the same from anyone who holds your proof.

| You expect a bank to… | Expect an identity provider to… |
| --- | --- |
| Check who you are when you open an account | Run both checks carefully, with defenses against fakes |
| Lock the vault | Encrypt what it stores, and keep only what it needs |
| Let only you in | Use keys like passkeys, not quiz questions |
| Ask before money moves | Ask before sharing anything, and share only what's needed |
| Send statements | Show where you used your identity, and what it shared |
| Help when something goes wrong | Offer a fair way back in, and a path for people without standard documents |
| Answer to outside checks | Pass outside reviews, such as FedRAMP for government work |

After a decade of breaches, the fair question is why anyone should trust a provider with more. Two answers matter most.

**Outside standards.** Under federal rules like NIST's security controls and FedRAMP, an independent assessor checks that a provider encrypts what it stores, uses tested encryption, and controls who can reach the data. That's different from a company saying it takes security seriously. Standards lower the risk without ending it. OPM was a federal agency under federal security rules, and it was still breached.

**Design.** A passkey's private key stays on your device. The provider holds only a matching public key, which is useless to a thief. So a breach of the provider can't hand out the key you sign in with.

Not every provider does all of this. If you're choosing one, ask which outside reviews it has passed. The addendum at the end lists the main ones.

> **The fix in three lines**
>
> 1. Let a trusted provider you choose prove who you are, once.
> 2. Sign in with a key that phishing and AI can't steal.
> 3. Claim your identity first, then reuse it wherever it's accepted.

So does it end identity theft?

## Part 4. The limits

### Does this end identity theft?

No.

**Your data doesn't disappear.** This is where identity differs from cash in a bank. Copies of your facts from Equifax and every other breach still exist, and they always will. The goal is to make them less useful.

**It only helps where it's accepted.** It does nothing at a lender that still approves applications on matching facts.

**The side doors matter.** A strong front door means little if a thief can get through account recovery with your birth date. Organizations have to guard sign-up and recovery too. And real people who lose their phone still need a fair way back in. Passkeys move one door too. Synced passkeys live in your Apple or Google account, so that account's recovery becomes a door worth guarding.

![A building labeled your account. The front door, sign in, is locked. Two side doors, sign-up and account recovery, are dashed. A thief heads toward the sign-up door.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/16-side-doors.png)

**It can't stop you from being talked into it.** A strong identity check stops someone pretending to be you. It doesn't stop a scammer who convinces the real you to send money. People 60 and older reported $4.9 billion in losses to the FBI in 2024. Imposter scams cost people $2.95 billion that year, the FTC says. Against these, a family code word and a call back on a number you know still matter most.

**Every check trusts the ID.** A real license obtained with a forged birth certificate passes every test. GAO investigators got licenses in three states using counterfeit documents.

**Nobody insures your identity.** The FDIC backs your deposits. Nothing like it backs your identity, so the cleanup still falls on you.

**Fair concerns remain.** One provider holding many verified identities makes a bigger target, as the breaches above show. Reusing one proof everywhere could make you easier to track. And not everyone has a driver's license, a smartphone, a long history, or a face match that works well for them. Current federal guidelines add other paths, such as a trained person who reviews the case. And when a provider wrongly rejects a real person, someone has to fix it fast. A bank has a fraud line and a dispute process. A provider needs the same. I'll come back to each of these in later posts.

So this is a shared job. Providers protect the proof. Organizations decide what proof they accept. People protect their keys. I'd like more places to accept strong proof, with real choice of provider. That's a direction to build toward, not how things work everywhere today.

So far, this has all been about protection. But a bank doesn't just keep your money safe. Could a proven identity do more than keep thieves out?

## Part 5. The upside

### What could a proven identity earn you?

Think about cash in a mattress. It's hidden, and it's yours. But it just sits there, and it isn't that safe. Put it in a bank, and two things change. It's guarded, and it goes to work. You pay bills, get paid, and build a credit history that opens doors later. Banks still get robbed. The point is that safety and use can live together.

![Left: cash under a mattress, hidden but hard to use. Right: a bank, guarded and easy to use for paying bills, sending money and buying things.](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/17-mattress.png)

Most people treat their identity like cash in a mattress. Hide it, and hope. A proven identity can go to work too.

Nobody pays you interest just for being verified. The value shows up when someone honors your proof.

![Four uses of a proven identity: claim what you qualify for (a confirmed teacher badge), skip the paperwork (documents already proven), share less (prove over 21 without a birth date), and grow it over time (degree, license, service).](https://raw.githubusercontent.com/jchip/blog-assets/main/identity-1/18-uses.png)

Money goes unclaimed even from programs people qualify for. The IRS says about 1 in 5 eligible workers didn't claim the Earned Income Tax Credit in tax year 2022. Part of the fix is knowing what you qualify for. Part is proving it easily.

The store or program still pays for the benefit. Your identity just proves you qualify.

Your personal data already earns money today, just not for you. The FTC says data brokers collect it "largely without consumers' knowledge," then sell it. A proven identity you control is the opposite deal. You choose what to share, and you share it to get something you want.

Today it's still hard to see most of this. Where is my verified identity accepted? What do I already qualify for? What would I have to share to claim it?

And there's a bigger gap. Your bank card works almost anywhere. Does your proven identity?

### Why doesn't my proof work everywhere?

Banks compete, but they also connect. Your card works at another bank's ATM. Money moves between banks every day over shared networks.

Identity providers mostly don't work that way yet. There are many of them, and proving yourself with one usually doesn't count where another is accepted. So you end up proving yourself again with each new company.

People are working on it in a few ways:

- **Shared standards.** Mobile driver's licenses follow an international standard, so one reader can check licenses from many states. Common sign-in standards let one provider vouch for you at many sites.
- **Shared rulebooks.** The EU requires every member country to offer a digital identity wallet by the end of 2026, and it has to work across the EU. The UK and Canada publish trust frameworks, rules that providers can be certified against.
- **Banks as identity providers.** In Sweden and Norway, banks issue digital IDs, each called BankID. People use them to sign in to public and private services.

How identity providers could connect the way banks do is a topic for another post.

### What's already coming?

Some of this is taking shape. Digital credentials let a business check who issued a claim and whether anyone changed it. Mobile driver's licenses are one example, and digital wallets hold them. Federal pilots are testing how mobile licenses can work with Login.gov.

AI agents are next. In 2025, Visa and Mastercard announced ways for AI agents to shop and pay on a person's behalf. That raises a new identity question: which human sent this agent, and what did they allow it to do? Researchers have also proposed personhood credentials, which prove you're a real person online without saying who you are. Both are topics for another post.

### What's still open?

These are the questions I want to take on next:

- Could identity providers connect the way banks do?
- What happens when I lose my phone?
- Can identity get easier to prove without getting easier to track?
- When an AI agent acts for me, how does anyone know I sent it?

Guarding your identity will always matter. It just doesn't have to be the whole story.

If your identity were something you could safely put to work, what would you want it to do for you? And if you build sign-up or recovery flows, do they ask both questions?

---

## Addendum: terms and standards

For readers who want the details behind the plain-language version.

### The two checks, in NIST's words

NIST writes the federal government's digital identity guidelines, SP 800-63, now in its fourth revision.

- **Validation** is the facts check. It confirms the evidence is genuine and its details are accurate.
- **Verification** is the person check. It confirms the applicant holds the claimed real-life identity. NIST also uses "verifier" for confirming someone controls an authenticator.
- **Identity proofing** is validation plus verification, done once at enrollment.
- **Authentication** is showing you still control your credential each time you return.
- **Federation** is a provider sending a signed assertion about you to another business, the "relying party."

The guidelines split into three volumes, matching the three steps.

| Step | Volume |
| --- | --- |
| Prove | SP 800-63A, identity proofing |
| Protect | SP 800-63B, authentication |
| Present | SP 800-63C, federation |

### Quizzes and AI controls

- SP 800-63A-4 says knowledge-based verification "SHALL NOT be used for identity verification." The 2017 revision allowed it with limits.
- SP 800-63B-4 requires checking new passwords against a blocklist of commonly used, expected, or compromised passwords.
- SP 800-63B-4 lists phone codes as a "restricted" authenticator. It says verifiers "SHOULD consider risk indicators (e.g., device swap, SIM change, number porting, other abnormal behavior)" before sending one.
- SP 800-63A-4 requires controls against digital injection and forged media. They raise confidence that a camera feed comes from a real camera.
- For people without standard documents, SP 800-63A-4 adds trusted referees and applicant references.

### Digital credentials

- The W3C, which sets web standards, describes proving an age threshold without a full birth date as data minimization.
- NIST's National Cybersecurity Center of Excellence is demonstrating how mobile driver's licenses can work with Login.gov.

### Interoperability efforts

- **Mobile driver's licenses.** ISO/IEC 18013-5 is the standard for in-person reading. ISO/IEC TS 18013-7 is a technical specification for online use. AAMVA's Digital Trust Service lets businesses verify licenses from participating states.
- **Sign-in and credentials.** OpenID Connect is the common standard for signing in through an identity provider. The OpenID Foundation also publishes OpenID for Verifiable Presentations.
- **Trust frameworks.** EU eIDAS 2.0, Regulation (EU) 2024/1183, created the EU Digital Identity Wallet. The UK publishes the digital verification services trust framework. Canada's DIACC publishes the Pan-Canadian Trust Framework. The Open Identity Exchange works on interoperability between frameworks.

### Synthetic identity

The Federal Reserve defines synthetic identity fraud as using personal information "to fabricate a person or entity" for a dishonest gain.

### Outside reviews of providers

- **FedRAMP.** The security program for cloud services sold to federal agencies. It's run by GSA, and Congress wrote it into law in 2022. An independent assessor reviews the service against NIST SP 800-53 controls. Each agency still decides whether to use it. A review covers one specific service, not everything a company does. FedRAMP is recasting its Low, Moderate, and High levels as classes.
- **Encryption.** At the moderate and high baselines, SP 800-53 calls for protecting data at rest (SC-28) and in transit (SC-8). At rest means stored. In transit means moving. Federal systems must use encryption validated under NIST's Cryptographic Module Validation Program, against FIPS 140. A vendor saying "we encrypt" isn't the same as encryption that passed that test.
- **Kantara Initiative.** A nonprofit that assesses identity providers against SP 800-63. Agencies may recognize its trust mark.
- **GovRAMP.** A FedRAMP-style program for states.
- **IRS Publication 1075.** Requires federal tax data to stay on systems in the United States.
- **Banks.** The FFIEC publishes guidance on authentication and access. The FDIC insures deposits up to $250,000 per depositor, per bank.

---

## Sources

- GSA, [Login.gov](https://www.login.gov/what-is-login/), [IAL2 certification](https://www.gsa.gov/about-us/newsroom/news-releases/gsas-logingov-announces-certification-of-ial2-10092024)
- SSA, [Creating a my Social Security account](https://www.ssa.gov/myaccount/creating-an-account.html); IRS, [Creating an account for IRS.gov](https://www.irs.gov/help/creating-an-account-for-irsgov)
- CLEAR, [CLEAR1 credential policy](https://clearme.com/clear-verified-credential-policy-crp)
- TSA, [Digital ID participating states](https://www.tsa.gov/digital-id/participating-states)
- IRS, [EITC participation rate](https://www.irs.gov/tax-professionals/eitc-central/eitc-participation-rate-by-state). 80.8% for tax year 2022.
- FTC, [Data broker report](https://www.ftc.gov/news-events/news/press-releases/2014/05/ftc-recommends-congress-require-data-broker-industry-be-more-transparent-give-consumers-greater), May 2014
- FTC, [What to know about identity theft](https://consumer.ftc.gov/articles/what-know-about-identity-theft)
- FTC, [Consumer Sentinel Network Data Book 2024](https://www.ftc.gov/system/files/ftc_gov/pdf/csn-annual-data-book-2024.pdf). 1,135,291 identity theft reports; 449,032 credit card. Reports are not unique victims.
- Bureau of Justice Statistics, [Victims of Identity Theft, 2021](https://bjs.ojp.gov/library/publications/victims-identity-theft-2021), [Table 4](https://bjs.ojp.gov/document/vit21.pdf#page=7). Survey of U.S. residents 16 and older; published October 2023. Acquisition breakdown covers only the 21% of victims who knew how.
- Identity Theft Resource Center, [2025 Annual Data Breach Report](https://www.idtheftcenter.org/wp-content/uploads/2026/01/2025-ITRC-Annual-Data-Breach-Report.pdf#page=9), Figure 1. Publicly reported U.S. compromises; counts incidents, not people.
- SSA, [Social Security cards through the years](https://www.ssa.gov/history/ssn/ssnversions.html)
- CFPB, [Equifax settlement over the 2017 data breach](https://www.consumerfinance.gov/about-us/newsroom/cfpb-ftc-states-announce-settlement-with-equifax-over-2017-data-breach)
- SSA, [my Social Security publication](https://www.ssa.gov/pubs/EN-05-10064.pdf)
- IRS, [Get an Identity Protection PIN](https://www.irs.gov/identity-theft-fraud-scams/get-an-identity-protection-pin)
- Federal Reserve, [Synthetic identity fraud definition](https://fedpaymentsimprovement.org/news/press-releases/federal-reserve-system-announces-industry-recommended-definition-of-synthetic-identity-fraud/)
- NIST, [SP 800-63-4 overview](https://pages.nist.gov/800-63-4/sp800-63.html), [800-63A-4 identity proofing](https://pages.nist.gov/800-63-4/sp800-63a.html), [800-63B-4 authentication](https://pages.nist.gov/800-63-4/sp800-63b.html), [800-63C-4 federation](https://pages.nist.gov/800-63-4/sp800-63c.html)
- Nacha, [About Nacha and the ACH Network](https://www.nacha.org/about)
- ISO, [ISO/IEC 18013-5](https://www.iso.org/standard/69084.html), [ISO/IEC TS 18013-7](https://www.iso.org/standard/91154.html); AAMVA, [Digital Trust Service](https://aamva.org/identity/mobile-driver-license-digital-trust-service)
- European Commission, [European Digital Identity Regulation](https://digital-strategy.ec.europa.eu/en/policies/eudi-regulation); EUR-Lex, [Regulation (EU) 2024/1183](https://eur-lex.europa.eu/eli/reg/2024/1183/oj)
- GOV.UK, [UK digital identity and attributes trust framework collection](https://www.gov.uk/government/collections/uk-digital-identity-and-attributes-trust-framework); DIACC, [Pan-Canadian Trust Framework](https://diacc.ca/trust-framework-components/pctf-overview); [Open Identity Exchange](https://openidentityexchange.org/)
- [BankID Sweden](https://www.bankid.com/en/); Norwegian Digitalisation Agency, [eID in Norway](https://eid.difi.no/en)
- OpenID Foundation, [How OpenID Connect works](https://openid.net/developers/how-connect-works/), [OpenID for Verifiable Presentations 1.0](https://openid.net/specs/openid-4-verifiable-presentations-1_0-final.html)
- NIST, [SP 800-63B-4 authenticators](https://pages.nist.gov/800-63-4/sp800-63b/authenticators/), section 3.1.3.3
- FBI IC3, [SIM swapping PSA](https://www.ic3.gov/PSA/2022/PSA220208), February 8, 2022; FCC, [SIM swap and port-out rules](https://www.govinfo.gov/content/pkg/FR-2023-12-08/pdf/2023-26338.pdf), Federal Register, December 8, 2023
- IRS, [Statement on the Get Transcript application](https://www.irs.gov/newsroom/irs-statement-on-the-get-transcript-application); Journal of Accountancy, [Get Transcript breach worse](https://www.journalofaccountancy.com/news/2016/feb/irs-get-transcript-data-breach-worse-201613967.html), February 2016
- Federal Reserve, [Synthetic identity fraud white paper release](https://www.federalreserve.gov/newsevents/pressreleases/other20190709a.htm), July 2019
- FBI IC3, [2024 Internet Crime Report](https://www.ic3.gov/AnnualReport/Reports/2024_IC3Report.pdf). Phishing/spoofing: 193,407 complaints.
- CISA, [Implementing phishing-resistant MFA](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf), October 2022
- Pew Research Center, [Mobile fact sheet](https://www.pewresearch.org/internet/fact-sheet/mobile/)
- Apple, [iPhone 5s and Touch ID](https://www.apple.com/newsroom/2013/09/10Apple-Announces-iPhone-5s-The-Most-Forward-Thinking-Smartphone-in-the-World/), 2013; [iPhone X and Face ID](https://www.apple.com/newsroom/2017/09/the-future-is-here-iphone-x/), 2017
- NIST, [Face recognition demographic effects (NISTIR 8280)](https://www.nist.gov/news-events/news/2019/12/nist-study-evaluates-effects-race-age-sex-face-recognition-software), December 2019
- Yahoo/Oath, [2013 breach update, SEC filing](https://www.sec.gov/Archives/edgar/data/732712/000073271217000003/a2017_10x3xoathxexhibitx991.htm), October 2017
- FTC, [Action against Marriott and Starwood](https://www.ftc.gov/news-events/news/press-releases/2024/10/ftc-takes-action-against-marriott-starwood-over-multiple-data-breaches), October 2024
- OPM, [Cybersecurity incidents](https://www.opm.gov/cybersecurity/cybersecurity-incidents/); GAO, [GAO-17-614](https://www.gao.gov/products/gao-17-614)
- HHS, [Anthem resolution agreement](https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/agreements/anthem/index.html)
- FTC, [Equifax settlement](https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach), July 2019
- Capital One, [2019 incident release, SEC filing](https://www.sec.gov/Archives/edgar/data/927628/000092762819000262/exhibit991-pressrelease72919.htm)
- AT&T, [Addressing a data set released on the dark web](https://about.att.com/story/2024/addressing-data-set-released-on-dark-web.html), 2024
- FTC, [Lost or stolen credit, ATM, and debit cards](https://consumer.ftc.gov/articles/lost-or-stolen-credit-atm-and-debit-cards); BJS, [Victims of Identity Theft, 2021 report](https://bjs.ojp.gov/document/vit21.pdf)
- FTC, [Free credit freezes, 2018](https://www.ftc.gov/news-events/press-releases/2018/09/starting-today-new-law-allows-consumers-place-free-credit-freezes); [Credit freezes and fraud alerts](https://consumer.ftc.gov/articles/what-know-about-credit-freezes-fraud-alerts)
- New York Attorney General, [Credential stuffing alert to 17 companies](https://ag.ny.gov/press-release/2022/attorney-general-james-alerts-17-companies-credential-stuffing-cyberattacks), January 2022; FTC, [Recover a hacked email account](https://consumer.ftc.gov/articles/how-recover-your-hacked-email-or-social-media-account)
- Apple, [About passkeys](https://support.apple.com/en-us/102195); Google, [Passkeys FAQ](https://developers.google.com/identity/passkeys/faq)
- FBI IC3, 2024 report (elder fraud: 147,127 complaints, $4.885 billion); FTC, [Fraud losses of $12.5 billion in 2024](https://www.ftc.gov/news-events/news/press-releases/2025/03/new-ftc-data-show-big-jump-reported-losses-fraud-125-billion-2024)
- GAO, [GAO-12-893, driver's license fraud](https://www.gao.gov/products/gao-12-893), September 2012
- Visa, [Visa Intelligent Commerce](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21361.html), April 2025; Mastercard, [Agent Pay](https://www.mastercard.com/us/en/news-and-trends/press/2025/april/mastercard-unveils-agent-pay-pioneering-agentic-payments-technology-to-power-commerce-in-the-age-of-ai.html), April 2025; OpenID Foundation, [Identity management for agentic AI](https://openid.net/new-whitepaper-tackles-ai-agent-identity-challenges/), October 2025
- Adler et al., [Personhood credentials](https://arxiv.org/abs/2408.07892), 2024
- NIST, [Digital injection prevention and forged media detection](https://pages.nist.gov/800-63-4/sp800-63a.html#digital-injection-prevention-and-forged-media-detection)
- W3C, [Verifiable Credentials Data Model 2.0, data minimization](https://www.w3.org/TR/vc-data-model-2.0/#the-principle-of-data-minimization)
- NIST NCCoE, [Mobile driver's license project](https://www.nccoe.nist.gov/projects/digital-identities-mdl), [Login.gov demonstration](https://www.nccoe.nist.gov/node/2986)
- FBI IC3 public service announcements: [December 3, 2024](https://www.ic3.gov/psa/2024/psa241203), [May 15, 2025](https://www.ic3.gov/PSA/2025/PSA250515), [December 19, 2025](https://www.ic3.gov/PSA/2025/PSA251219), [July 20, 2026](https://www.ic3.gov/PSA/2026/PSA260720)
- FinCEN, [Alert on fraud schemes involving deepfake media](https://fincen.gov/news/news-releases/fincen-issues-alert-fraud-schemes-involving-deepfake-media-targeting-financial), November 13, 2024
- 404 Media, [Inside the underground site where AI churns out fake IDs](https://www.404media.co/inside-the-underground-site-where-ai-neural-networks-churns-out-fake-ids-onlyfake/), February 2024
- CNN, [Arup revealed as $25 million deepfake scam victim](https://abc17news.com/money/cnn-business-consumer/2024/05/16/british-engineering-giant-arup-revealed-as-25-million-deepfake-scam-victim/), May 2024
- FTC, [Fighting back against harmful voice cloning](https://consumer.ftc.gov/consumer-alerts/2024/04/fighting-back-against-harmful-voice-cloning)
- FFIEC, [Authentication and access to financial institution services](https://www.ffiec.gov/guidance/Authentication-and-Access-to-Financial-Institution-Services-and-Systems.pdf)
- FDIC, [Understanding deposit insurance](https://www.fdic.gov/resources/deposit-insurance/understanding-deposit-insurance/)
- GSA, [FedRAMP](https://www.gsa.gov/technology/government-it-initiatives/fedramp); FedRAMP, [law](https://fedramp.gov/2026/authority/law/), [agency duties](https://fedramp.gov/2026/agencies/), [FedRAMP's role](https://fedramp.gov/2026/responsibilities/fedramp/), [assessors](https://fedramp.gov/2026/responsibilities/assessors/)
- NIST, [SP 800-53 Rev 5 baselines (OSCAL)](https://github.com/usnistgov/oscal-content/tree/main/nist.gov/SP800-53/rev5/json): SC-28 and SC-8 in the moderate and high baselines
- NIST, [Cryptographic Module Validation Program](https://csrc.nist.gov/projects/cryptographic-module-validation-program), [FAQ](https://csrc.nist.gov/projects/cryptographic-module-validation-program/faqs), [FIPS 140-3](https://csrc.nist.gov/pubs/fips/140-3/final)
- Kantara Initiative, [Trust Status List](https://kantarainitiative.org/trust-status-list/); GSA, [idmanagement.gov cloud playbook](https://www.idmanagement.gov/playbooks/cloud/)
- GovRAMP, [StateRAMP rebrand to GovRAMP](https://govramp.org/news/blog/stateramp-announces-rebrand-to-govramp-reflecting-mission-to-unite-public-and-private-sectors-in-advancing-cybersecurity), February 2025
- IRS, [Cloud computing environment (Publication 1075)](https://www.irs.gov/privacy-disclosure/cloud-computing-environment)
