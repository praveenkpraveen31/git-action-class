GitHub Context:

```
github.repository        Owner/repo name
github.actor            Triggering user
github.ref              Full reference
github.ref_name         Short reference
github.sha              Commit SHA
github.event_name       Event type
github.event            Event details
github.workspace        Working directory
github.action           Action name
github.action_path      Action directory
github.action_ref       Action reference
github.action_status    Action status
```

Runner Context:

```
runner.os               Operating system
runner.arch             Architecture
runner.temp             Temporary directory
runner.tool_cache       Tools cache directory
```

Job Context:

```
job.status              Current job status
job.container           Container info
job.services            Services info
```

Steps Context:

```
steps.STEP_ID.outcome   Step outcome
steps.STEP_ID.conclusion Step conclusion
steps.STEP_ID.outputs   Step outputs
```