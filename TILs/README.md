# IDA Type Information Libraries

| Type Informaiton Library     | Description                                                                                                                                |
|:-----------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------|
| [`mscoru.til`]               | Microsoft Common Object Runtime (Unmanaged .NET), used when reversing numerous [unmanaged .NET code injection techniques][Red Team Notes]. |
| `thewover_donut_v*.til`      | [TheWover/Donut] position-independent shellcode, often a dependency of payload generation tools such as [PoshC2].                          |
| `thewover_donut_kali_v*.til` | [Kali's TheWover/Donut] position-independent shellcode, often a dependency of payload generation tools such as [PoshC2].                   |

[`mscoru.til`]: ./mscoru.til
[Red Team Notes]: https://www.ired.team/offensive-security/code-injection-process-injection/injecting-and-executing-.net-assemblies-to-unmanaged-process
[TheWover/Donut]: https://github.com/TheWover/donut
[Kali's TheWover/Donut]: https://gitlab.com/kalilinux/packages/donut-shellcode
[PoshC2]: https://github.com/nettitude/PoshC2
