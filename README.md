<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sankalp Management & Consultant Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: black;
            color: white;
            text-align: center;
        }
        header {
            background-color: red;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        section {
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .service-box {
            background: white;
            color: black;
            padding: 15px;
            border-radius: 8px;
            width: 300px;
            text-align: left;
        }
        footer {
            background: red;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        form {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            color: black;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        button {
            background: red;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        Sankalp Management & Consultant Services
    </header>

    <section>
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-box">
                <h3>Society Management Services</h3>
                <ul>
                    <li>Compliance with Maharashtra Co-Op. Societies Act, 1960.</li>
                    <li>Maintenance of statutory records (I & J registers, Share registers, etc.).</li>
                    <li>Coordination with BMC, Registrar, and legal professionals.</li>
                    <li>Financial operations: cheque deposits, withdrawals, bill payments.</li>
                    <li>Vendor management for efficient operations.</li>
                </ul>
            </div>
            <div class="service-box">
                <h3>Accounting Services</h3>
                <ul>
                    <li>Billing, receipt updates, and vendor payments.</li>
                    <li>Maintenance of cash books, cheque books, ledgers.</li>
                    <li>Daily financial tracking and office operations.</li>
                    <li>Preparation of Income & Expenditure statements.</li>
                    <li>Account finalization with statutory auditors.</li>
                </ul>
            </div>
            <div class="service-box">
                <h3>Other Facilities</h3>
                <ul>
                    <li>Legal advisory for conveyance, redevelopment, society matters.</li>
                    <li>Filing of Section 101 notices for recovery.</li>
                    <li>Society elections and training.</li>
                    <li>Provision of Society, Facility, and Accounts Managers.</li>
                    <li>Vendor-managed housekeeping and security services.</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        &copy; 2025 Sankalp Management & Consultant Services
    </footer>
</body>
</html>
