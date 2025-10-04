# Schéma Firestore (MVP)

Toutes les collections sont liées à un utilisateur (uid).

## users/{uid}/moods
- value: number (1–5)
- note: string
- createdAt: timestamp

## users/{uid}/baby_sleep
- startAt: timestamp
- endAt: timestamp
- note: string?

## users/{uid}/baby_feed
- type: "breast" | "bottle" | "solid"
- amount: number?
- at: timestamp

## users/{uid}/tasks
- title: string
- dueAt: timestamp?
- status: "todo" | "done"

## users/{uid}/expenses
- amount: number
- category: string
- note: string?
- at: timestamp
