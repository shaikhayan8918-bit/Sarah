# Sarah
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Consistent Yoga Practice for a Stronger, Calmer You</title>
    <style>
        /* CSS Reset/Normalization */
        *, *::before, *::after { box-sizing: border-box; }
        html, body, div, span, h1, h2, h3, p, a, img, ul, li { margin: 0; padding: 0; border: 0; font-size: 100%; font: inherit; vertical-align: baseline; }
        body { line-height: 1.6; }
        ul { list-style: none; }

        /* General Styles */
        html, body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
            background-color: #F8F7F4;
            color: #333;
            overflow-x: hidden;
        }

        .container {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Typography & Spacing */
        h1, h2, h3 {
            font-weight: 700;
            line-height: 1.2;
            color: #2c3e50;
            margin-bottom: 20px;
        }
        h1 { font-size: 2.5rem; text-align: center; }
        h2 { font-size: 2rem; border-left: 4px solid #7D9D9C; padding-left: 15px; margin-top: 50px; }
        p { margin-bottom: 20px; font-size: 1.1rem; max-width: 650px; }
        .center-text { text-align: center; margin-left: auto; margin-right: auto; }

        /* Hero Section */
        .hero { background-color: #E4EFE7; text-align: center; padding: 60px 20px; }
        .preheader { font-size: 1rem; font-weight: 600; color: #576F72; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 1px; }
        .hero h1 { color: #2c3e50; }
        .hero .subheader { font-size: 1.2rem; color: #333; max-width: 600px; margin: 20px auto 30px; }
        .vsl-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 0 auto 30px;
            cursor: pointer;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .vsl-container img {
            width: 100%;
            height: auto;
            display: block;
        }
        .play-button {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80px;
            height: 80px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: transform 0.2s ease, background-color 0.2s ease;
        }
        .play-button:hover { transform: translate(-50%, -50%) scale(1.1); background-color: white; }
        .play-button::after {
            content: '';
            width: 0;
            height: 0;
            border-top: 15px solid transparent;
            border-bottom: 15px solid transparent;
            border-left: 25px solid #E84A5F;
            margin-left: 5px;
        }

        /* Buttons */
        .cta-button {
            display: inline-block;
            background-color: #E84A5F;
            color: #fff;
            padding: 18px 40px;
            font-size: 1.2rem;
            font-weight: 700;
            text-decoration: none;
            border-radius: 50px;
            box-shadow: 0 5px 15px rgba(232, 74, 95, 0.4);
            transition: background-color 0.2s ease, transform 0.2s ease;
            border: none;
            cursor: pointer;
        }
        .cta-button:hover { background-color: #d13c4f; transform: translateY(-3px); }

        /* Content Sections */
        .section { padding: 50px 0; }
        .section-break { border-top: 1px solid #ddd; margin: 40px auto; width: 80%; }
        
        /* Bullets */
        .benefits-list { padding-left: 20px; }
        .benefits-list li {
            font-size: 1.1rem;
            margin-bottom: 25px;
            padding-left: 40px;
            position: relative;
        }
        .benefits-list li::before {
            content: '✔';
            position: absolute;
            left: 0;
            top: 0;
            color: #7D9D9C;
            font-size: 1.5rem;
            font-weight: bold;
        }
        .benefits-list li strong { color: #2c3e50; display: block; }

        /* Offer & FAQ */
        .offer-box {
            background-color: #fff;
            border: 2px solid #E4EFE7;
            border-radius: 8px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        .price { font-size: 2.5rem; font-weight: bold; color: #2c3e50; margin-bottom: 5px; }
        .price-term { font-size: 1rem; color: #555; margin-bottom: 20px; }
        .guarantee { margin-top: 20px; font-style: italic; color: #555; }
        .faq-item {
            border-bottom: 1px solid #eee;
            padding-bottom: 15px;
            margin-bottom: 15px;
        }
        .faq-item:last-child { border-bottom: none; }
        .faq-question { font-weight: bold; font-size: 1.1rem; color: #2c3e50; cursor: pointer; position: relative; }
        .faq-question::after { content: '+'; position: absolute; right: 0; }
        details[open] .faq-question::after { content: '–'; }
        .faq-answer { margin-top: 10px; color: #333; }

        /* Responsive Design */
        @media (max-width: 768px) {
            h1 { font-size: 2rem; }
            h2 { font-size: 1.75rem; }
            .container { padding: 20px 15px; }
            .hero { padding: 40px 15px; }
        }
    </style>
</head>
<body>

    <section class="hero">
        <div class="container">
            <p class="preheader">For the busy woman whose wellness is always last on the list</p>
            <h1>Get a Stronger, Calmer Body in Just 15 Minutes a Day… With the Daily Yoga Calendar That Finally Makes Your Practice Stick.</h1>
            <p class="subheader">Without the expensive studio fees, the confusing YouTube rabbit holes, or feeling lost about what to do next.</p>
            
            <div class="vsl-container">
                <img src="https://i.imgur.com/Pq3n2sJ.jpg" alt="Woman doing yoga at home, looking calm and focused.">
                <div class="play-button"></div>
            </div>

            <a href="#offer" class="cta-button">Start Your 30-Day Free Trial</a>
        </div>
    </section>

    <main class="container">

        <section class="section">
            <h2>Does That Yoga Mat in the Corner Look Familiar?</h2>
            
            <p>You bought it with the best intentions.</p>
            <p>You pictured yourself greeting the sun, moving with ease, feeling that post-yoga calm settle over you before the day’s chaos could hit.</p>
            <p>But reality looks… different.</p>
            <p>Some days you unroll it, open YouTube, and get paralyzed. A million videos shout at you. "10 Minute Fat Burn!" "90 Minute Advanced Flow!" "Yoga for... everything!"</p>
            <p>You spend 10 minutes just *choosing*, and by then, the dog needs to go out or a work email pings.</p>
            <p>So the mat gets rolled back up.</p>
            <p>Other days, you think about that expensive studio membership you bought. You do the mental math. Driving there, finding parking, the one-hour class, the drive back... it’s a two-hour commitment you just don't have.</p>
            <p>The guilt sets in. The stiffness in your back gets a little worse. The feeling of being constantly on-edge becomes your new normal.</p>
            <p>You know you need this. You *want* this. But making it happen feels impossible.</p>
            <p>It’s not your fault. And there's a much simpler way.</p>
        </section>

        <div class="section-break"></div>

        <section class="section">
            <h2>The "Decision-Free" Discovery Born from Burnout</h2>
            
            <p>Like you, I was drowning in responsibilities. Juggling work, family, and a never-ending to-do list, my own well-being was an afterthought.</p>
            <p>I knew yoga was the answer. I’m a yoga teacher, after all! But even I struggled to practice at home.</p>
            <p>Free online classes were a mess of ads and interruptions. Studio schedules never aligned with my actual life. I was missing the one thing that kept me grounded.</p>
            <p>The problem wasn't the *yoga*. It was the *friction*.</p>
            <p>The biggest hurdle every single day was the simple question: "What should I do today?"</p>
            <p>That’s when I realized the solution wasn't a better video or a fancier pose. It was removing that one question entirely.</p>
            <p>So I created a simple calendar for myself. Each day had one single class assigned to it. No searching. No deciding. Just press play.</p>
            <p>Suddenly, my practice became non-negotiable. It was as simple as brushing my teeth. In 15 or 20 minutes, I was done. I felt centered, my body felt open, and I was a better parent and professional for it.</p>
            <p>That personal system is what I want to share with you.</p>
        </section>

        <div class="section-break"></div>

        <section class="section">
            <h2>The Daily Yoga Calendar: Your Personal Path to Consistency</h2>
            
            <p>Imagine waking up, opening an app, and seeing one single yoga session waiting for you. It’s the perfect length for your day. It’s exactly what your body needs. You just press play.</p>
            <p>That’s the core of this entire system. It’s designed to eliminate the mental energy that keeps you from your mat.</p>
            <p>Here’s what this feels like:</p>
            
            <ul class="benefits-list">
                <li>
                    <strong>The Daily Yoga Calendar</strong> that tells you exactly which class to take each day, which removes all guesswork so you feel motivated and clear. You become the person who shows up for herself, consistently.
                </li>
                <li>
                    <strong>An exclusive library of over 850+ ad-free classes,</strong> from 5-minute morning stretches to full 60-minute flows, giving you complete control over your schedule. You feel capable and accomplished, even on your busiest days.
                </li>
                <li>
                    <strong>Downloadable videos for offline access,</strong> so you can practice anytime, anywhere—on a plane, in a hotel, or when the Wi-Fi is spotty. You are someone whose wellness routine is truly unstoppable.
                </li>
                <li>
                    <strong>Monthly LIVE classes and meditations,</strong> letting you connect in real-time for that "in-studio" energy without ever leaving your home. You feel a genuine sense of belonging and support.
                </li>
                <li>
                    <strong>Structured playlists for any goal</strong>—whether it’s for morning energy, evening calm, or postpartum recovery—providing a clear path to the results you want. You become confident in your ability to care for your body.
                </li>
                <li>
                    <strong>A private, in-app community of people just like you,</strong> where you can ask questions and share wins away from the noise of social media. You feel seen, heard, and never alone on your journey.
                </li>
                 <li>
                    <strong>Detailed pose breakdowns and tutorials,</strong> so you can learn proper alignment and build a safe, effective practice from the ground up. You become your own best teacher, moving with skill and awareness.
                </li>
            </ul>
        </section>

        <div class="section-break"></div>

        <section class="section">
            <h2>Introducing the SarahBethYoga App & Membership</h2>
            
            <p>This is more than just a collection of videos. It's a complete ecosystem designed to fit into your real life.</p>
            <p>Forget the distracting ads that break your focus right in the middle of a peaceful stretch. Forget the feeling of isolation when you practice alone.</p>
            <p>The SarahBethYoga app is your private, sacred space for wellness. It’s everything you need, all in one place, accessible on your phone, tablet, TV, or computer.</p>
            <p>You've tried the free route and felt overwhelmed. You've considered the studio and found it too demanding.</p>
            <p>This is the middle path. The sustainable path. It gives you the structure of a studio with the flexibility you desperately need. And at a fraction of the cost.</p>
        </section>

        <div class="section-break"></div>

        <section id="offer" class="section">
            <h2>Ready to Finally Make Your Practice Stick?</h2>
            
            <div class="offer-box">
                <p>Try Everything, Risk-Free, for 30 Days.</p>
                <p>For less than the cost of two drop-in studio classes, you get unlimited access to your own personal yoga guide, every single day of the month.</p>
                
                <p class="price">$39</p>
                <p class="price-term">PER MONTH, AFTER FREE 30-DAY TRIAL</p>
                <p>Or choose the annual plan for just <strong>$348/year</strong> and get two months free.</p>
                
                <a href="#" class="cta-button">Start My 30-Day Free Trial Now</a>
                
                <p class="guarantee">Your first month is completely free. If you don't feel calmer, stronger, and more consistent in your practice, you can cancel anytime with a click. No questions asked. Plus, your rate is locked in for life as long as you remain a member.</p>
            </div>
        </section>

        <div class="section-break"></div>

        <section class="section">
            <h2>Your Questions, Answered.</h2>

            <div class="faq-list">
                <details class="faq-item">
                    <summary class="faq-question">"Is this good for absolute beginners?"</summary>
                    <div class="faq-answer">
                        <p>Yes, absolutely. There are specific beginner calendars, playlists, and hundreds of classes designed for those just starting out. You’ll learn the foundations correctly and safely, building confidence from your very first session.</p>
                    </div>
                </details>

                <details class="faq-item">
                    <summary class="faq-question">"I have no time. Is this realistic for me?"</summary>
                    <div class="faq-answer">
                        <p>This was created *for* people with no time. With hundreds of classes under 20 minutes (and many just 5-10 minutes long), you can always fit it in. The goal isn't perfection; it's consistency. Five minutes a day is better than one hour a month.</p>
                    </div>
                </details>
                
                <details class="faq-item">
                    <summary class="faq-question">"Why pay when there's so much free yoga on YouTube?"</summary>
                    <div class="faq-answer">
                        <p>YouTube is a library; this is a guided path. You're not paying for videos—you're paying to eliminate decision fatigue. You get a daily calendar, structured programs, an ad-free experience, offline downloads, and a supportive community. It’s the difference between having a pile of bricks and having a blueprint to build your house.</p>
                    </div>
                </details>

                <details class="faq-item">
                    <summary class="faq-question">"What if I try it and it's not for me?"</summary>
                    <div class="faq-answer">
                        <p>That's exactly what the 30-day free trial is for. You get full, unlimited access to everything. If you don't love it, you can cancel with one click before the trial ends and you won't be charged a penny. There is zero risk.</p>
                    </div>
                </details>

                <details class="faq-item">
                    <summary class="faq-question">"What devices can I use this on?"</summary>
                    <div class="faq-answer">
                        <p>Everything! Your membership gives you access on iOS, Android, Apple TV, Roku, FireTV, and any web browser on your desktop or laptop. Your practice follows you wherever you go.</p>
                    </div>
                </details>
            </div>

            <div style="text-align: center; margin-top: 40px;">
                <p>That yoga mat doesn't have to be a reminder of something you "should" do.</p>
                <p>Starting today, it can be the place you go to find 15 minutes of strength, calm, and clarity.</p>
                <a href="#offer" class="cta-button">Claim Your 30-Day Free Trial</a>
            </div>
        </section>

    </main>

</body>
</html>
