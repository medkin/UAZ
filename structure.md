SsmsDmlGuard/
├── SsmsDmlGuard.csproj
├── source.extension.vsixmanifest
├── SsmsDmlGuardPackage.cs          — AsyncPackage + registers priority command target
├── QueryExecutionGuard.cs          — IOleCommandTarget implementation
├── SqlStatementAnalyzer.cs         — ScriptDom parsing
├── ServerConnectionHelper.cs       — Extracts server name from SSMS context
├── GuardConfiguration.cs           — JSON config read/watch
├── ConfirmationDialog.xaml/.cs     — WPF dialog
└── SsmsDmlGuardCommandTable.vsct   — VS Command Table for Tools menu