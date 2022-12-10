# raws

Plain text AWS event and identifier lists.
Initially devised to assist during automation efforts for Incident Response, Reconnoissance and SysAdmin tasks.

Anything missing? Well, add it and I will review your PR eventually! Or re run the parser so you obtain the latest available list. 


## How doe?

- Go to [https://docs.aws.amazon.com/index.html](https://docs.aws.amazon.com/index.html).
- Per service, go to the `API reference` > `Actions` section.
- Parse all the different actions and dump them into a plain-text file for that specific service.
- Bonus: Append them to a `Main.list` file where all the events are listed. 