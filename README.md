<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Startup</title>
  <style>
    /* Reset and basic styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      width: 1440px;       /* Fixed width */
      height: 9208px;      /* Very tall page */
      opacity: 1;          /* Fully visible */
      transform: rotate(0deg); /* No rotation */
      background-color: #f9f9f9;
      margin: 0 auto;      /* Center horizontally in viewport */
    }

    header {
      width: 100%;
      padding: 50px 0;
      background: #1a1a1a;
      color: #fff;
      text-align: center;
    }

    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 20px;
    }

    section {
      width: 100%;
      padding: 100px 80px;
    }

    section:nth-child(even) {
      background: #f0f0f0;
    }

    h2 {
      font-size: 36px;
      margin-bottom: 40px;
      text-align: center;
    }

    .features, .pricing {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }

    .feature, .plan {
      background: #fff;
      border-radius: 12px;
      padding: 30px;
      margin: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      flex: 1 1 250px;
      text-align: center;
    }

    .feature h3, .plan h3 {
      font-size: 24px;
      margin-bottom: 15px;
    }

    .cta {
      text-align: center;
      margin: 60px 0;
    }

    .cta button {
      padding: 20px 50px;
      font-size: 24px;
      border: none;
      border-radius: 8px;
      background-color: #1a1a1a;
      color: #fff;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .cta button:hover {
      background-color: #333;
    }

    footer {
      background: #1a1a1a;
      color: #fff;
      text-align: center;
      padding: 50px 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>AI Startup</h1>
    <p>Revolutionize Your Workflow with Smart AI Tools</p>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p style="text-align:center; max-width: 800px; margin: 0 auto;">
      We’re on a mission to make AI accessible for everyone. Our platform automates tedious tasks, predicts trends, and helps teams make smarter decisions—without needing to write a single line of code.
    </p>
  </section>

  <section id="features">
    <h2>Features</h2>
    <div class="features">
      <div class="feature">
        <h3>Smart Automation</h3>
        <p>Automate repetitive tasks in seconds, saving hours of work.</p>
      </div>
      <div class="feature">
        <h3>Data Insights</h3>
        <p>Turn raw data into actionable insights with AI analysis.</p>
      </div>
      <div class="feature">
        <h3>Collaboration</h3>
        <p>AI-powered recommendations for your team’s best workflow.</p>
      </div>
      <div class="feature">
        <h3>Integrations</h3>
        <p>Works seamlessly with tools like Slack, Gmail, and more.</p>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <div class="pricing">
      <div class="plan">
        <h3>Free</h3>
        <p>$0 / month</p>
        <p>Basic AI features, limited usage</p>
      </div>
      <div class="plan">
        <h3>Starter</h3>
        <p>$19 / month</p>
        <p>Full automation, 5 projects</p>
      </div>
      <div class="plan">
        <h3>Pro</h3>
        <p>$49 / month</p>
        <p>Unlimited projects, priority support</p>
      </div>
      <div class="plan">
        <h3>Enterprise</h3>
        <p>Custom</p>
        <p>Custom integrations, dedicated support</p>
      </div>
    </div>
  </section>

  <section class="cta">
    <button>Get Started</button>
  </section>

  <footer>
    <p>© 2026 AI Startup. All Rights Reserved.</p>
  </footer>

</body>
</html>

