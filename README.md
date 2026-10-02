<div align="center">🟣 PabloPanel

A modern VPN control panel built for gaming.

Clean client links. Live statistics. Beautiful subscription pages.

<br><img src="https://img.shields.io/badge/PabloPanel-Dark%20Neon-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Railway-Ready-8B5CF6?style=for-the-badge&logo=railway&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Ready-8B5CF6?style=for-the-badge&logo=docker&logoColor=white" /></div>---

«💜 Tip

Fork → Deploy on Railway → Expose port "8080" → Open PabloPanel.

Four simple steps. No complicated setup.»

<br><table>
<tr>
<td width="50%">🎮 Gaming Interface

A dark neon gaming UI designed for a fast and clean experience on both mobile and desktop.

</td>
<td width="50%">⚡ Simple Management

Create, manage, enable, disable and remove users directly from the dashboard.

</td>
</tr><tr>
<td width="50%">📊 Live Statistics

View users, active accounts, traffic usage and server information from one dashboard.

</td>
<td width="50%">🔗 Subscription System

Every user gets a dedicated subscription page with their real configurations and account information.

</td>
</tr><tr>
<td width="50%">📱 Mobile Friendly

The dashboard and subscription pages are fully designed to work smoothly on phones.

</td>
<td width="50%">🟣 Neon Design

A dark interface with purple / neon accents inspired by modern gaming dashboards.

</td>
</tr>
</table>---

👤 Users

PabloPanel gives you a simple way to manage your VPN users.

- Create users
- Enable / disable accounts
- Delete users
- View traffic usage
- View subscription links
- Copy configurations
- Open user subscription pages

---

📡 Subscription

A dedicated page is generated for every user.

It includes:

Username · Status · Traffic · Remaining Volume · Remaining Days · Subscription URL

And also provides:

- 📋 Copy subscription
- 📋 Copy all configurations
- 📱 QR codes
- ⚡ Individual configuration actions
- 🎮 Gaming section

---

📊 Dashboard

The dashboard gives you a quick overview of your panel.

Users

Active Users

Total Traffic

Used Traffic

Server Status

Everything important is available from one place.

---

🚀 Deploy

1. Fork

Fork this repository to your GitHub account.

2. Railway

Create a new Railway project and select your repository.

3. Deploy

Railway automatically builds the project using the included "Dockerfile".

4. Port

Expose:

8080

5. Open

Open your Railway domain and enter PabloPanel.

---

«⚠️ Important

PabloPanel uses port "8080" for the web panel.

Only expose the port required by the panel.»

---

⚙️ Configuration

Setting| Value
Panel| PabloPanel
Port| "8080"
Platform| Railway
Container| Docker
Theme| Dark Neon
Interface| Responsive

---

📁 Structure

PabloPanel/
│
├── static/
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   └── subscription.html
│
├── app.py
├── Dockerfile
└── requirements.txt

---

<div align="center">🟣 PabloPanel

VPN Control · Subscriptions · Gaming

Built to look different.

</div>
