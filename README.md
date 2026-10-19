# Help Desk Labs

Hands-on help desk and IT support labs by Keenian Knott (Security+, working toward CompTIA A+). Each lab is written up like a real ticket: the scenario, how I troubleshot it, how I fixed it, and what I'd do differently in production.

## Labs

| Lab | Platform | Topics |
|-----|----------|--------|
| [VPN disconnected and won't reconnect](servicedesk-simulator/vpn-disconnect-ticket/) | ServiceDesk Simulator v2.7 | Remote Desktop, DNS cache flush, VPN client, user communication |
| [New hire account setup](servicedesk-simulator/new-hire-account-setup/) | ServiceDesk Simulator | Active Directory user creation, security groups, onboarding, ticket ownership |
| [Nobody on the 3rd floor has internet](servicedesk-simulator/floor3-network-outage/) | ServiceDesk Simulator | Network outage scoping, server room devices, switch restart, critical ticket |
| [Second monitor shows "No Signal"](servicedesk-simulator/second-monitor-no-signal/) | ServiceDesk Simulator | Hardware vs software isolation, display driver update, System Update tool |

## Related labs

- [Entra ID & Active Directory Lab Series](https://github.com/keenianknott91-ops/entra-ad-lab-series): Microsoft Entra ID users and groups, plus identity lifecycle tickets (new hire, name change, termination, transfer). Password reset and MFA labs are next.
- [osTicket Help Desk Lab](https://github.com/keenianknott91-ops/osticket-helpdesk-lab): osTicket deployed with Docker, with an example ticket worked to closure.

*More simulator tickets will be added to this repo as I complete them.*
