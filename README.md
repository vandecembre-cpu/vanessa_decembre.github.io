[index.html](https://github.com/user-attachments/files/31930852/index.html)
# vanessa_decembre.github.io<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Vanessa Decembre — Product Strategy & Operations</title>
  <meta name="description" content="Vanessa Decembre is a product strategy and operations leader in San Francisco who takes products from dev-complete to in-market — building the systems, partnerships, and operating rhythms that make launches stick.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #fbfaf7;
      --surface: #ffffff;
      --ink: #1a1a1a;
      --ink-2: #4a4a4a;
      --ink-3: #7a7a7a;
      --line: #e6e2da;
      --accent: #1f5f4e;
      --accent-soft: #e6f0ec;
      --max: 860px;
      --serif: "Fraunces", Georgia, "Times New Roman", serif;
      --sans: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--ink);
      font-family: var(--sans);
      font-size: 17px;
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; text-underline-offset: 3px; }
    .wrap { max-width: var(--max); margin: 0 auto; padding: 0 24px; }

    /* Nav */
    header {
      position: sticky; top: 0; z-index: 10;
      background: rgba(251,250,247,0.9);
      backdrop-filter: blur(8px);
      border-bottom: 1px solid var(--line);
    }
    nav { display: flex; align-items: center; justify-content: space-between; height: 60px; }
    nav .brand { font-family: var(--serif); font-weight: 600; font-size: 18px; color: var(--ink); }
    nav ul { list-style: none; display: flex; gap: 24px; margin: 0; padding: 0; }
    nav ul a { color: var(--ink-2); font-size: 14px; font-weight: 500; }
    nav ul a:hover { color: var(--accent); text-decoration: none; }

    /* Hero */
    .hero { padding: 96px 0 72px; }
    .eyebrow { font-size: 13px; font-weight: 600; letter-spacing: 0.08em; text-transform: uppercase; color: var(--accent); margin: 0 0 16px; }
    h1 { font-family: var(--serif); font-weight: 500; font-size: clamp(36px, 6vw, 56px); line-height: 1.1; letter-spacing: -0.01em; margin: 0 0 20px; }
    .lede { font-size: 20px; color: var(--ink-2); max-width: 640px; margin: 0 0 32px; }
    .cta { display: flex; gap: 14px; flex-wrap: wrap; align-items: center; }
    .btn {
      display: inline-block; padding: 12px 20px; border-radius: 6px; font-weight: 500; font-size: 15px;
      background: var(--accent); color: #fff; border: 1px solid var(--accent);
    }
    .btn:hover { text-decoration: none; background: #17493c; }
    .btn.ghost { background: transparent; color: var(--accent); }
    .btn.ghost:hover { background: var(--accent-soft); }

    /* Sections */
    section { padding: 64px 0; border-top: 1px solid var(--line); }
    h2 { font-family: var(--serif); font-weight: 500; font-size: 30px; margin: 0 0 8px; letter-spacing: -0.01em; }
    .sub { color: var(--ink-3); margin: 0 0 36px; font-size: 16px; }
    p { margin: 0 0 16px; }

    /* Stats */
    .stats { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 16px; margin-top: 40px; }
    .stat { border: 1px solid var(--line); background: var(--surface); border-radius: 8px; padding: 18px 20px; }
    .stat b { display: block; font-family: var(--serif); font-size: 28px; font-weight: 600; color: var(--ink); line-height: 1.1; }
    .stat span { font-size: 14px; color: var(--ink-3); }

    /* Case studies */
    .cases { display: grid; gap: 20px; }
    .case {
      background: var(--surface); border: 1px solid var(--line); border-radius: 10px; padding: 28px 28px 24px;
    }
    .case .meta { font-size: 13px; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: var(--accent); margin: 0 0 8px; }
    .case h3 { font-family: var(--serif); font-weight: 600; font-size: 22px; margin: 0 0 12px; line-height: 1.25; }
    .case p { color: var(--ink-2); font-size: 16px; }
    .case .result { margin: 14px 0 0; padding-top: 14px; border-top: 1px dashed var(--line); font-size: 15px; color: var(--ink); }
    .case .result strong { color: var(--accent); font-weight: 600; }

    /* Experience */
    .role { display: grid; grid-template-columns: 150px 1fr; gap: 24px; padding: 22px 0; border-bottom: 1px solid var(--line); }
    .role:last-child { border-bottom: 0; }
    .role .when { color: var(--ink-3); font-size: 14px; padding-top: 4px; }
    .role h3 { margin: 0 0 4px; font-size: 18px; font-weight: 600; }
    .role .title { color: var(--ink-2); font-size: 15px; margin: 0 0 8px; }
    .role p { font-size: 15px; color: var(--ink-2); margin: 0; }

    /* Skills */
    .tags { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
    .tag { font-size: 14px; padding: 6px 12px; border-radius: 999px; background: var(--accent-soft); color: var(--accent); font-weight: 500; }

    /* Contact / footer */
    .contact p { max-width: 560px; }
    footer { padding: 32px 0 48px; color: var(--ink-3); font-size: 14px; border-top: 1px solid var(--line); }
    footer .row { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 8px; }

    @media (max-width: 640px) {
      nav ul { gap: 16px; }
      nav ul li:nth-child(n+4) { display: none; }
      .hero { padding: 64px 0 48px; }
      .role { grid-template-columns: 1fr; gap: 4px; }
      .case { padding: 22px; }
    }
  </style>
</head>
<body>

<header>
  <div class="wrap">
    <nav>
      <a class="brand" href="#top">Vanessa Decembre</a>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<main id="top">

  <div class="hero"><div class="wrap">
    <p class="eyebrow">Product Strategy &amp; Operations · San Francisco</p>
    <h1>I take products from dev-complete to in-market.</h1>
    <p class="lede">I build the systems, partnerships, and operating rhythms that make launches stick — from 0-to-1 financial products in Haiti to the operating cadence behind a Salesforce sales org.</p>
    <div class="cta">
      <a class="btn" href="mailto:vandecembre@gmail.com">Get in touch</a>
      <a class="btn ghost" href="https://www.linkedin.com/in/vanessa-decembre/" target="_blank" rel="noopener">LinkedIn</a>
    </div>
  </div></div>

  <section id="about">
    <div class="wrap">
      <h2>About</h2>
      <p class="sub">Builder and fixer, with a researcher's temperament.</p>
      <p>I've spent the last decade at the seam between strategy and execution — as a consultant at Accenture, a business development lead at Uber, Chief of Staff to a Sales SVP at Salesforce, and most recently leading product strategy and operations at Nclusion, a fintech serving underbanked communities.</p>
      <p>The pattern across all of it: I'm handed something ambiguous — a roadmap with no launch plan, a backlog nobody has prioritized, an operating review that's become a fight about data — and I turn it into a system people keep using after I've moved on. I care about defining terms up front ("tested," "launched," "done"), earning trust by understanding how people actually work before asking them to change, and measuring what matters.</p>
      <p>I hold an MBA from the Wharton School (University of Pennsylvania) and a BA in Sociology and African American Studies from Harvard. I work in English and French, with working Haitian Creole.</p>

      <div class="stats">
        <div class="stat"><b>4</b><span>financial products launched 0→1 in Haiti</span></div>
        <div class="stat"><b>~2 wks</b><span>from dev-complete to in-market, per product</span></div>
        <div class="stat"><b>$55M+</b><span>projected five-year savings, MBTA procurement</span></div>
        <div class="stat"><b>5%</b><span>sales uplift from a late-quarter recovery plan</span></div>
      </div>
    </div>
  </section>

  <section id="work">
    <div class="wrap">
      <h2>Selected work</h2>
      <p class="sub">Five projects that show how I operate.</p>

      <div class="cases">

        <article class="case">
          <p class="meta">Nclusion · 0→1 launch · 2025–present</p>
          <h3>Taking four financial products to market in Northern Haiti</h3>
          <p>Joined with products that were dev-complete but had no playbook, no agent network, and no way to test in-market. Defined what "launch" meant for each product (first agent live, first transaction), built training and playbooks with a small local team, and set deliberately small initial targets so we could learn fast.</p>
          <p>Alongside the launches, I built a sandbox environment from scratch — hired testers, wrote the end-to-end playbook, and made the case that "tested" had to mean full happy-and-unhappy-path coverage, not just the happy path. The wallet launch proved it: we caught OTP failures, card-activation friction, and a security gap where a scanned ticket could be cashed twice, all before a live customer was touched.</p>
          <p class="result"><strong>Result:</strong> Dev-complete to in-market in roughly two weeks per product. Grew the network from zero to ~200 agents and ~1,400 cards. Product backlog cut from ~100 stalled items to 25 actionable ones through a triage system product still uses.</p>
        </article>

        <article class="case">
          <p class="meta">Salesforce · Operating rhythm · 2024–2025</p>
          <h3>Turning a contentious QBR into a forum for decisions</h3>
          <p>As Chief of Staff to a Sales SVP, I inherited monthly and quarterly business reviews where half of every session was spent arguing about whether the numbers were right. The SVP didn't trust the data, and the previous team hadn't built the relationship.</p>
          <p>I added a pre-read layer: before every review, I walked the SVP and her AVPs through the data one-on-one so they could question it before the room filled up. Relationship first, then rigor. When year-over-year analysis showed we were ~$10M behind with a quarter to go, I raised it early rather than at close and built the recovery plan with product marketing — bundles, rep playbooks, targeted incentive periods.</p>
          <p class="result"><strong>Result:</strong> By the second review, the conversation had moved from data disputes to pipeline decisions. The late-quarter push delivered a ~5% sales uplift. I also coached my one analyst to a promotion he'd previously been passed over for.</p>
        </article>

        <article class="case">
          <p class="meta">Uber · Partnerships · 2023–2024</p>
          <h3>Building an e-bike battery safety program from zero</h3>
          <p>In 2023 a wave of e-bike battery fires in New York put public pressure on Uber to do more for couriers on the platform. It wasn't a revenue play; it was about courier safety and how the city saw us. I had roughly $100K and a mandate to move quickly without locking Uber in.</p>
          <p>I selected a certified battery and e-bike partner, structured the deal (one-year term, exit at any time, 10–20% discount, net-90 invoicing, joint-statement rights), deployed the fund across battery swaps, charging, and bikes, defined the KPIs, and handed it to operations to run.</p>
          <p class="result"><strong>Result:</strong> ~300 couriers enrolled against 100 bikes, fully utilized within weeks with a waitlist. The program kept running through 2024, after my role ended. Separately, I took a Portland airport shuttle from concept to first ride in under three months.</p>
        </article>

        <article class="case">
          <p class="meta">Accenture · Product delivery · 2018–2020</p>
          <h3>Shipping a sales enablement tool in half the usual time</h3>
          <p>Field reps and marketers at a large pharmaceutical client were logging customer interactions in a clunky legacy tool. I was the product manager on the replacement, leading four to five offshore engineers and client stakeholders as a team of one on the consulting side.</p>
          <p>I mapped the customer journey with reps, wrote the requirements, ran twice-weekly standups, and scoped the MVP on one rule: everything on the end-to-end flow ships first; anything off the flow goes to the roadmap. When Legal wanted to edit contract language in-tool, that went to a later release — the MVP needed to get a standard contract through, not customize one.</p>
          <p class="result"><strong>Result:</strong> Deployed in about six months against a typical nine-to-twelve, with the next-release roadmap already defined.</p>
        </article>

        <article class="case">
          <p class="meta">Accenture · Procurement strategy · 2018–2020</p>
          <h3>Running vendor selection for MBTA paratransit routing</h3>
          <p>The MBTA's paratransit service needed a better routing tool, and the transit team needed a selection process they could trust. I defined requirements with the paratransit team, issued an RFI that drew six to eight vendors, shortlisted three to four, ran interviews and hands-on assessments, and built an evaluation model scoring each vendor against requirements, terms, and the status-quo budget.</p>
          <p class="result"><strong>Result:</strong> Vendor selected in 10–12 weeks, with $55M+ in projected five-year savings versus the status quo through more efficient routing and escalators negotiated into the deal.</p>
        </article>

      </div>
    </div>
  </section>

  <section id="experience">
    <div class="wrap">
      <h2>Experience</h2>
      <p class="sub">Where I've worked.</p>

      <div class="role">
        <div class="when">2025 – Present</div>
        <div>
          <h3>Nclusion</h3>
          <p class="title">Product Strategy &amp; Operations, Go-to-Market · San Francisco</p>
          <p>Go-to-market execution for financial inclusion products serving underbanked communities. Led 0-to-1 launches in Haiti, built the testing sandbox and product triage process, and established the requirements and prioritization framework across four workstreams.</p>
        </div>
      </div>

      <div class="role">
        <div class="when">2024 – 2025</div>
        <div>
          <h3>Salesforce</h3>
          <p class="title">Sales Strategy &amp; Operations · Chief of Staff to SVP, Sales · San Francisco</p>
          <p>Ran the operating rhythm for a Sales SVP and her AVPs. Executive communications, SQL-driven analysis, contingency planning, and change management across GTM, product, and executive teams. Managed one analyst.</p>
        </div>
      </div>

      <div class="role">
        <div class="when">2022 – 2024</div>
        <div>
          <h3>Uber</h3>
          <p class="title">Business Development &amp; Membership Strategy · San Francisco</p>
          <p>Structured partnership terms and legal agreements for policy and sustainability programs, launched two 0-to-1 supply-side programs, and contributed competitive strategy for the Uber One membership.</p>
        </div>
      </div>

      <div class="role">
        <div class="when">2016 – 2020</div>
        <div>
          <h3>Accenture</h3>
          <p class="title">Consultant (2018–2020) · Analyst, Senior Analyst (2016–2018) · Boston</p>
          <p>Operations, procurement, analytics, and product delivery across public sector, pharmaceutical, and asset management clients. Led an 8-person cross-functional team through a full product lifecycle; ran a $55M+ transit procurement.</p>
        </div>
      </div>

      <div class="role">
        <div class="when">Education</div>
        <div>
          <h3>The Wharton School, University of Pennsylvania</h3>
          <p class="title">MBA, Applied Consumer Behavior · 2022</p>
          <h3 style="margin-top:14px">Harvard University</h3>
          <p class="title">BA, Sociology &amp; African American Studies · 2016</p>
        </div>
      </div>

      <h2 style="margin-top:56px; font-size:24px">How I work</h2>
      <div class="tags">
        <span class="tag">0→1 launches</span>
        <span class="tag">Operating rhythms &amp; OKRs</span>
        <span class="tag">Executive communications</span>
        <span class="tag">Cross-functional leadership</span>
        <span class="tag">Partnership &amp; deal structuring</span>
        <span class="tag">Product requirements &amp; prioritization</span>
        <span class="tag">KPI dashboards &amp; analytics</span>
        <span class="tag">Change management</span>
        <span class="tag">Frontier-market delivery</span>
        <span class="tag">SQL · Excel · JIRA · AI &amp; automation</span>
        <span class="tag">English · French · Haitian Creole</span>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="wrap">
      <h2>Contact</h2>
      <p class="sub">I'm exploring product strategy, business operations, and Chief of Staff roles.</p>
      <p>The best way to reach me is email. I'm especially interested in teams building or expanding into new markets, and in seats with real strategic and operational ownership.</p>
      <div class="cta">
        <a class="btn" href="mailto:vandecembre@gmail.com">vandecembre@gmail.com</a>
        <a class="btn ghost" href="https://www.linkedin.com/in/vanessa-decembre/" target="_blank" rel="noopener">linkedin.com/in/vanessa-decembre</a>
      </div>
    </div>
  </section>

</main>

<footer>
  <div class="wrap row">
    <span>© 2026 Vanessa Decembre</span>
    <span>San Francisco, CA</span>
  </div>
</footer>

</body>
</html>
