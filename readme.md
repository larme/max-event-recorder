an event recorder for Max

# What's the difference between this and [seq~]?

- The event data is editable inside max because it use [coll] to store all events.

- Use [timer] to calculate event timing so you can use tick instead of ms as time unit

- not as "loopy" as [seq~]

- not as accurate as [seq~]

# TODO

- [x] er.gated: record in alternative time format (update:add ticks support 2013-07-23)
- [ ] er.gated: overdub recording (a little bit tricky)
- [ ] er.player: vary playback speed (you can use ticks and the event playback will be synced to global transport update:2013-07-23)
- [ ] er.player: output time point
- [ ] er.trimmer: trim the "silence" at the beginning of a string of events
- [ ] er.shifter: shift events (in positive time direction)
- [ ] er.chopper: chop events either evenly or based on specific time points
- [ ] er.visualizer: visualize events in [function] object
- [x] max help file
