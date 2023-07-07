## Conditional Jobs &  Steps
 - Control Stap or Job execution with if & dynamic expressions
 - Change default behavior with failure(), success(), canselled(), or always()
 - Use continue-on-error to ignore Step failure

## Matrix Jobs
 - Run multiple Job configurations in parallel
 - Add or remove individual combinations
 - Control whether a single failing Job should cancel all other Matrix Jobs via continue-on-error

## Resuable Workflows
 - Workflows can be resused via the workflow_call event
 - Reuse any logic (as many Jobs $ Steps as needed)
 - Work with inputs, outputs and secrets as required