# GSoC_Work
A brief report on GSoC'16 with Zulip

**Organization**: Zulip

**Project Name**: Overhauling Zulip website’s UX to handle large teams

**Abstract**: To improve existing features and add new features, to create a more robust and agile version of web version of Zulip which can handle large teams. A user will be able to use it more intuitively.

**Student Name**: Kartik Maji

**Mentor**: [Neeraj Wahi](https://github.com/neerajwahi) and [acrefoot](https://github.com/acrefoot)

|Code Link   |Description   |Status   |Future possible works|Screenshots|
|---|---|---|---|---|
| https://github.com/zulip/zulip/pull/749/commits  |Narrowing to a non-existing stream should display a error message. Issue: https://github.com/zulip/zulip/issues/740 | Work in progress  |   |   |
| https://github.com/zulip/zulip/pull/525/commits  | List # of subscribers for each stream (https://github.com/zulip/zulip/issues/483)   |  Work in progress |   |   |
| https://github.com/zulip/zulip/pull/819/commits  |Pin favourite or important streams to top of stream list   |**Merged**   |Pin stream to always open. (https://github.com/zulip/zulip/pull/986) Issue:https://github.com/zulip/zulip/issues/292   |   |
| https://github.com/zulip/zulip/pull/857/commits  |Add search box for searching people when creating new stream.   |**Merged**   |This feature is very slow in Production especially when organisation is large(~500 users). Issue: https://github.com/zulip/zulip/issues/1509, https://github.com/zulip/zulip/pull/1617/   |   |
| https://github.com/zulip/zulip/pull/913/commits  |Add stream search box in left sidebar and subscription page.   |Closed   |Partial work of this PR was merged by https://github.com/zulip/zulip/pull/684. We still need to develop stream filter for subscription page for which user can refer either PR913 or https://github.com/zulip/zulip/pull/711.   |   |
| https://github.com/zulip/zulip/pull/1063/commits  |Correctly narrow to stream when using search box. Reference https://github.com/zulip/zulip/issues/1012   |**Merged**   |   |   |
|https://github.com/zulip/zulip/pull/1468/commits   |Show correct error message when narrowed to silent and non existent users. Reference: https://github.com/zulip/zulip/issues/1418   |**Merged**   |   |   |
|https://github.com/zulip/zulip/pull/850/commits |Similar to "pin to top" stream, user can star other users. Starred users will be sorted to top of Right sidebar user list. |Work in progress |May be automatically star users based on interaction history |   |
|https://github.com/zulip/zulip/pull/1101/commits |Improves visibility of unread global messages count when narrowed to a particular stream. |Work in progress | |   |
|https://github.com/zulip/zulip/pull/1122/commits |Give users a set of permission(can read, can write etc.) for each stream. |Work in progress | |   |
|https://github.com/zulip/zulip/pull/1204/commits |UI to details of message edit history like edited by, timestamp, edited text. |Work in progress |Fixing message edit history template. See https://github.com/zulip/zulip/issues/1406 |   |
|https://github.com/zulip/zulip/pull/1432/commits |Don't allow users to mute a "mandatory" stream |Work in progress |Develop similar function where user cannot unsubscribe from mandatory stream. |   |
|https://github.com/zulip/zulip/pull/986/commits |Mark stream to always remain open |Closed | |   |

Note: Work in progress as on 25th August, 2016

