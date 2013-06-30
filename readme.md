an event recorder for Max

# What's the difference between this and [seq~]?

- The event data is editable inside max because it use [coll] to store all events.

- Use [timer] to calculate event timing so you can use tick instead of ms as time unit (in a future update)

- not as "loopy" as [seq~]

- not as accurate as [seq~]

# TODO

- er.gated: record in alternative time format
- er.gated: overdub recording (a little bit tricky)
- er.player: vary playback speed
- er.player: output time point
- er.trimmer: trim the "silence" at the beginning of a string of events
- er.shifter: shift events
- er.chopper: chop events either evenly or based on specific time points
- er.visualizer: visualize events in [function] object
- max help file
