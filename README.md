See more in https://chromium.googlesource.com/chromiumos/docs/+/HEAD/glossary.md


| Abbr/Word | Full/Meaning   | Chinese/Explain    | Note/Utilize     |
| --- | --- | --- | --- |
| NIT[^1]          | nit-pick                                            | 鸡蛋里面挑骨头              |                                                              |
| LGTM[^2]         | Looks Good To Me                                    | 代码已经过 review, 可以合并 |                                                              |
| ASAP[^2]         | As Soon As Possible                                 | 尽快                        |                                                              |
| ACK[^2]          | Acknowledgement                                     | 承认, 确认, 同意            | i.e. agreed/accepted change                                  |
| NACK/NAK[^2]     | Negative acknowledgement                            | 不同意                      | i.e. disagree with change and/or concept                     |
| RFC[^2]          | Request For Comments                                | 请求进行讨论                | i.e. I think this is a good idea, lets discuss               |
| WIP[^2]          | Work In Progress                                    | <p>进展中</p><p>传说中提 PR 的最佳实践是, 如果你有个改动很大的 PR, 可以在写了一部分的情况下先提交, 但是在标题里写上 WIP, 以告诉项目维护者这个功能还未完成, 方便维护者提前 review 部分提交的代码[^3]</p>                  |  |
| AFAIK/AFAICT[^2] | As Far As I Know / Can Tell                         | 据我所知/就我所知           |                                                              |
| IIRC[^2]         | If I Recall Correctly                               | 如果我没有记错的话          |                                                              |
| IANAL[^2]        | I am not a lawyer , but I smell licensing issues    | -                           |                                                              |
| IMO[^2]          | In My Opinion                                       | 在我看来                    |                                                              |
| TL;DR[^2]        | Too Long; Don’t Read                               | 太长别看                    |                                                              |
| CR[^2]           | Code Review                                         | 代码审查                    |                                                              |
| PTAL[^2]         | Please Take A Look                                  | 用来提示别人来看一下                            |                                         |
| TBR[^2]          | To Be Reviewed                                      |提示维护者进行 review                           |                                         |
| TBD[^2]          | To Be Done(or Defined/Discussed/Decided/Determined) | <p>未完成, 将被做</p><p>根据语境不同意义有所区别, 但一般都是还没搞定的意思</p>           |            |
| TBH[^2]          | To Be Honest                                        | 老实说                      |                                                              |
| ATM[^2]          | At The Moment                                       | 现阶段                      |                                                              |
| ABNF[^4][^5]     | Augmented BNF for Syntax Specifications             | 扩充巴科斯-瑙尔范式           |   形如: `规则 = 定义;注释CR LF `                           |
| Sink             | Sink to consume something, in this case a configurable constant current of electricity[^6] | （电流）可见到不可见[^7] | Java function 中 Consumer[^8] |
| Source | Source would mean to produce[^6] | （电流）不可见到可见[^7] | Java function 中 Supplier[^9] |

----

> Feel free to push new [word](https://github.com/bxb100/hacker-speak-abbreviations/issues/new?labels=word)


### Refer

[^1]: https://stackoverflow.com/questions/27810522/what-does-nit-mean-in-hacker-speak Stack Overflow
[^2]: https://zhuanlan.zhihu.com/p/385599914 ZhiHu
[^3]: https://farer.org/2017/03/01/code-review-acronyms/ Farer Blog
[^4]: https://zh.wikipedia.org/wiki/%E6%89%A9%E5%85%85%E5%B7%B4%E7%A7%91%E6%96%AF%E8%8C%83%E5%BC%8F ZH Wiki
[^5]: https://datatracker.ietf.org/doc/html/rfc5234 RFC-5234
[^6]: https://english.stackexchange.com/questions/261759/what-do-source-and-sink-mean
[^7]: https://en.wikipedia.org/wiki/Current_sources_and_sinks
[^8]: https://docs.spring.io/spring-cloud-stream/docs/3.2.1/reference/html/spring-cloud-stream.html#:~:text=the%20example%20of%20a-,sink,-semantics%20exposed%20as
[^9]: https://docs.spring.io/spring-cloud-stream/docs/3.2.1/reference/html/spring-cloud-stream.html#:~:text=the%20example%20of%20a-,source,-semantics%20exposed%20as

