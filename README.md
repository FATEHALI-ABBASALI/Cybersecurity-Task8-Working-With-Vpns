<h1>Working with VPNs — Task Report</h1>

<p><strong>Note:</strong> Task title was corrected from "Identify and Remove Suspicious Browser Extensions" (mistaken in original brief) to "Working with VPNs".</p>

<h3>Objective</h3>
<p>Hands-on experience with VPN setup, connection verification, and understanding privacy & encryption benefits/limitations.</p>

<h3>Tools used</h3>
<p>ProtonVPN free tier (recommended in task brief), Windscribe (optional). Web verification sites: whatismyipaddress.com, speedtest.net, ipleak.net.</p>

<h3>Step-by-step procedure</h3>

<pre>
1. Sign up for ProtonVPN (or Windscribe) on the official website.
2. Download and install the official client for your OS (Windows/macOS/Linux/Android/iOS).
3. Launch the VPN client and sign in.
4. Select a server (nearest recommended) and click "Connect".
5. Verify connection:
   - Visit https://whatismyipaddress.com and take a screenshot (connected).
   - Disconnect the VPN and visit the same site; take screenshot (disconnected).
6. Test speed:
   - While connected, run https://www.speedtest.net and take screenshot.
   - Disconnect and run it again; take screenshot.
7. Optional: run DNS leak test at https://ipleak.net and WebRTC leak checks.
8. Document results, write summary, commit README and screenshots to GitHub.
</pre>

<h3>Verification evidence (what to capture)</h3>
<table>
  <tr>
    <td>Connected IP screenshot</td>
    <td>screenshots/connected-ip.png</td>
  </tr>
  <tr>
    <td>Disconnected IP screenshot</td>
    <td>screenshots/disconnected-ip.png</td>
  </tr>
  <tr>
    <td>Speed test (connected)</td>
    <td>screenshots/speedtest-connected.png</td>
  </tr>
  <tr>
    <td>Speed test (disconnected)</td>
    <td>screenshots/speedtest-disconnected.png</td>
  </tr>
</table>

<h3>Short analysis: benefits & limitations</h3>
<p><strong>Benefits:</strong> encrypts traffic on untrusted networks, hides your IP, prevents local network eavesdropping, enables access to geo-restricted content (within policy limits).</p>
<p><strong>Limitations:</strong> provider can see metadata and may log data, some free providers throttle or limit servers, does not prevent fingerprinting or identification via cookies/logins, potential DNS/WebRTC leaks if misconfigured.</p>

<h3>Interview Q&A (short answers)</h3>
<p><strong>What is a VPN?</strong> A Virtual Private Network that creates an encrypted tunnel between your device and a remote server.</p>
<p><strong>Difference between VPN and proxy?</strong> VPN encrypts all traffic system-wide; proxy often affects only one app and may not encrypt.</p>
<p><strong>Common protocols:</strong> OpenVPN, WireGuard, IKEv2/IPSec, L2TP/IPSec.</p>

<h3>Notes</h3>
<p>Use official client downloads only. Capture screenshots immediately after connecting/disconnecting to ensure evidence accuracy. Do not use paid services unless you have authorization; use free tiers per the task instructions.</p>
