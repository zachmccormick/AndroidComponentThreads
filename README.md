[![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/zachmccormick?utm_source=github&utm_medium=button&utm_term=zachmccormick&utm_campaign=github)

If you ever wondered where the different Android components run by default:

Activity - always runs in UI/main thread

Local-process Service - runs on invoking thread

Local-process ContentProvider - runs on invoking thread

Remote-process ContentProvider - runs on a thread in a thread pool on remote application process

Remote-process (AIDL) Service - runs on a thread in a thread pool on remote application process

Local-process BroadcastReceiver - always runs in UI/main thread

Remote-process BroadcastReceiver - always runs in UI/main thread of remote process
