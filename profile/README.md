# DefacerID - Indonesian Cyber Attack Archive
DefacerID is the premier Indonesian Cyber Attack Archive. Stay updated on cyber intrusions and trends in a concise format.
<br><br>
<p align="center">
  email: <a href="mailto:admin@defacer.id">admin@defacer.id</a> / twitter: <a href="https://twitter.com/defacerid">@defacerid</a>
</p>
<br><br>

## Cyber Attack Archive

- General Archive https://defacer.id/archive
- Special Archive https://defacer.id/archive/special
- Cyber Attack Report https://defacer.id/cyber-attack-report

## APIs

### Get Cyber Attack Archive

- **Endpoint**: `api.defacer.id/cyber-attack-archive`
- **Method**: POST
- **Host**: `api.defacer.id`
- **Payload**:
  ```json
  {
    "archive": "archive",
    "page": 1
  }

- `archive`: Specifies the type of archive (`archive` for general, `special` for special, `car` for cyber attack report).
- `page`: Page number for paginated results.

### Submit/Notify

- **Endpoint**: `api.defacer.id/notify`
- **Method**: POST
- **Host**: `api.defacer.id`
- **Payload**:
  ```json
  {
    "notifier": "Name",
    "team": "Team",
    "url": "https://example.com",
    "poc": "Proof of Concept",
    "reason": "Reason"
  }

- `notifier`: Name of the notifier submitting the notification.
- `team`: Name of the team submitting the notification.
- `url`: URL of the affected website.
- `poc`: Proof of concept or details of the vulnerability.
- `reason`: Reason for reporting or notifying about the cyber attack.

## Resources

- Cyber Attack News: https://defacer.id/news and https://news.defacer.id
- Cyber Attack Profile: https://profile.defacer.id
- Cyber Attack Chatroom: https://chat.defacer.id
- Cyber Attack VDP: https://vdp.defacer.id
