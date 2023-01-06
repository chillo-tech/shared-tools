## Créer un exchange

- type: headers
- nom: tech.notifications.exchange

## Créer une queue

- type: headers
- nom: tech.notifications.queue

## Lier la queue à l'exchange

- arguments
  - x-match: any
  - application: \*
  - type: notification
