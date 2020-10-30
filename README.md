# UnoPlatformDevOps

A project to demonstrate using CI/CD for Uno Platform projects. From build to store release and everything in the middle.

### Build Pipelines

| Platform | main branch                              | releases branch                          |
|----------|------------------------------------------|------------------------------------------|
| UWP      | [![Main UWP](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Main%20UWP)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=53) | [![Release UWP](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Release%20UWP)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=54) |
| Android  | [![Main Android](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Main%20Android)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=55) | [![Release Android](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Release%20Android)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=57) |
| iOS      | [![Main iOS](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Main%20iOS)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=56) | [![Release iOS](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Release%20iOS)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=58) |
| Mac OS   | [![Main MacOS](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Main%20MacOS)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=60) | [![Release MacOS](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Release%20MacOS)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=59) |
| WASM     | [![Main WASM](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Main%20WASM)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=61) | [![Release WASM](https://dev.azure.com/lance/Uno%20Ops/_apis/build/status/Release%20WASM)](https://dev.azure.com/lance/Uno%20Ops/_build/latest?definitionId=62) |
| WPF | `n/a` | `n/a` |
| GTK | `n/a` | `n/a` |


### Release Pipelines

| Platform | Beta/TestFlight | Production |
|----------|-------|-----------|
| UWP      | [![Microsoft Store - Flight](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/1/1)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=1) | [![Microsoft Store - Production](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/1/2)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=1) |
| Android  | [![Google Play beta](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/2/3)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=2) |  [![Google Play Production](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/2/4)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=2) |
| iOS      | [![Apple TestFlight](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/3/5)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=3) | [![App Store Production](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/3/6)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=3) |
| MacOS    | `n/a` | `n/a` |
| WASM     | [![IIS staging](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/4/7)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=4) | [![Azure App Service](https://vsrm.dev.azure.com/lance/_apis/public/Release/badge/3ef55f14-06a9-4457-a69e-e52f945782d6/4/8)](https://dev.azure.com/lance/Uno%20Ops/_release?_a=releases&view=mine&definitionId=4) |
| WPF      | `n/a` | `n/a` |
| GTK      | `n/a` | `n/a` |


