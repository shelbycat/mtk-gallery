## Troubleshooting

Note: This project uses Yarn. If you have a problem on Windows that says `...AppData\Roaming\npm\yarn.ps1 cannot be loaded because running scripts is disabled on this system.`, then please check your execution policy with the following steps:

- `set-ExecutionPolicy RemoteSigned -Scope CurrentUser` (this sets your execution policy)
- `Get-ExecutionPolicy` it should show that the CurrentUser has ExecutionPolicty 'RemoteSigned', and everything else is 'Undefined'
- Then you can use yarn.
