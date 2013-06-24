an event recorder for Max

# What's the difference between this and [seq~]?

- The event data is editable inside max because it use [coll] to store all events.

- Use [timer] to calculate event timing so you can use tick instead of ms as time unit (in a future update)

- not as "loopy" as [seq~]
