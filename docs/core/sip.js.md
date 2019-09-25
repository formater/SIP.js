<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md)

## sip.js package

A core library implementing low level SIP protocol elements.

## Classes

|  Class | Description |
|  --- | --- |
|  [ByeUserAgentClient](./sip.js.byeuseragentclient.md) | BYE UAC. |
|  [ByeUserAgentServer](./sip.js.byeuseragentserver.md) | BYE UAS. |
|  [CancelUserAgentClient](./sip.js.canceluseragentclient.md) | CANCEL UAC. |
|  [ClientTransaction](./sip.js.clienttransaction.md) | Client Transaction. |
|  [Dialog](./sip.js.dialog.md) | Dialog. |
|  [Exception](./sip.js.exception.md) | An Exception is considered a condition that a reasonable application may wish to catch. An Error indicates serious problems that a reasonable application should not try to catch. |
|  [IncomingMessage](./sip.js.incomingmessage.md) | Incoming message. |
|  [IncomingRequestMessage](./sip.js.incomingrequestmessage.md) | Incoming request message. |
|  [IncomingResponseMessage](./sip.js.incomingresponsemessage.md) | Incoming response message. |
|  [InfoUserAgentClient](./sip.js.infouseragentclient.md) | INFO UAC. |
|  [InfoUserAgentServer](./sip.js.infouseragentserver.md) | INFO UAS. |
|  [InviteClientTransaction](./sip.js.inviteclienttransaction.md) | INVITE Client Transaction. |
|  [InviteServerTransaction](./sip.js.inviteservertransaction.md) | INVITE Server Transaction. |
|  [InviteUserAgentClient](./sip.js.inviteuseragentclient.md) | INVITE UAC. |
|  [InviteUserAgentServer](./sip.js.inviteuseragentserver.md) | INVITE UAS. |
|  [Logger](./sip.js.logger.md) | Logger. |
|  [LoggerFactory](./sip.js.loggerfactory.md) | Logger. |
|  [MessageUserAgentClient](./sip.js.messageuseragentclient.md) | MESSAGE UAS. |
|  [MessageUserAgentServer](./sip.js.messageuseragentserver.md) | MESSAGE UAS. |
|  [NameAddrHeader](./sip.js.nameaddrheader.md) | Name Address SIP header. |
|  [NonInviteClientTransaction](./sip.js.noninviteclienttransaction.md) | Non-INVITE Client Transaction. |
|  [NonInviteServerTransaction](./sip.js.noninviteservertransaction.md) | Non-INVITE Server Transaction. |
|  [NotifyUserAgentClient](./sip.js.notifyuseragentclient.md) | NOTIFY UAS. |
|  [NotifyUserAgentServer](./sip.js.notifyuseragentserver.md) | NOTIFY UAS. |
|  [OutgoingRequestMessage](./sip.js.outgoingrequestmessage.md) | Outgoing SIP request message. |
|  [PrackUserAgentClient](./sip.js.prackuseragentclient.md) | PRACK UAC. |
|  [PrackUserAgentServer](./sip.js.prackuseragentserver.md) | PRACK UAS. |
|  [PublishUserAgentClient](./sip.js.publishuseragentclient.md) | PUBLISH UAC. |
|  [ReferUserAgentClient](./sip.js.referuseragentclient.md) | REFER UAC. |
|  [ReferUserAgentServer](./sip.js.referuseragentserver.md) | REFER UAS. |
|  [RegisterUserAgentClient](./sip.js.registeruseragentclient.md) | REGISTER UAC. |
|  [RegisterUserAgentServer](./sip.js.registeruseragentserver.md) | REGISTER UAS. |
|  [ReInviteUserAgentClient](./sip.js.reinviteuseragentclient.md) | Re-INVITE UAC. |
|  [ReInviteUserAgentServer](./sip.js.reinviteuseragentserver.md) | Re-INVITE UAS. |
|  [ReSubscribeUserAgentClient](./sip.js.resubscribeuseragentclient.md) | Re-SUBSCRIBE UAC. |
|  [ReSubscribeUserAgentServer](./sip.js.resubscribeuseragentserver.md) | Re-SUBSCRIBE UAS. |
|  [ServerTransaction](./sip.js.servertransaction.md) | Server Transaction. |
|  [SessionDialog](./sip.js.sessiondialog.md) | Session Dialog. |
|  [SubscribeUserAgentClient](./sip.js.subscribeuseragentclient.md) | SUBSCRIBE UAC. |
|  [SubscribeUserAgentServer](./sip.js.subscribeuseragentserver.md) | SUBSCRIBE UAS. |
|  [SubscriptionDialog](./sip.js.subscriptiondialog.md) | Subscription Dialog. |
|  [Transaction](./sip.js.transaction.md) | Transaction. |
|  [TransactionStateError](./sip.js.transactionstateerror.md) | Indicates that the operation could not be completed given the current transaction state. |
|  [Transport](./sip.js.transport.md) | Transport. |
|  [TransportError](./sip.js.transporterror.md) | Transport error. |
|  [URI](./sip.js.uri.md) | URI. |
|  [UserAgentClient](./sip.js.useragentclient.md) | User Agent Client (UAC). |
|  [UserAgentCore](./sip.js.useragentcore.md) | User Agent Core. |
|  [UserAgentServer](./sip.js.useragentserver.md) | User Agent Server (UAS). |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [Levels](./sip.js.levels.md) | Log levels. |
|  [SessionState](./sip.js.sessionstate.md) | Session state. |
|  [SignalingState](./sip.js.signalingstate.md) | Offer/Answer state. |
|  [SubscriptionState](./sip.js.subscriptionstate.md) | Subscription state. |
|  [TransactionState](./sip.js.transactionstate.md) | Transaction state. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AckableIncomingResponseWithSession](./sip.js.ackableincomingresponsewithsession.md) | Incoming INVITE response received when request is accepted. |
|  [Body](./sip.js.body.md) | Message body. |
|  [ClientTransactionUser](./sip.js.clienttransactionuser.md) | UAC Core Transaction User. |
|  [Contact](./sip.js.contact.md) | Contact. |
|  [DialogState](./sip.js.dialogstate.md) | Dialog state. |
|  [IncomingAckRequest](./sip.js.incomingackrequest.md) | Incoming ACK request. |
|  [IncomingByeRequest](./sip.js.incomingbyerequest.md) | Incoming BYE request. |
|  [IncomingByeResponse](./sip.js.incomingbyeresponse.md) | Incoming BYE response. |
|  [IncomingCancelRequest](./sip.js.incomingcancelrequest.md) | Incoming CANCEL request. |
|  [IncomingCancelResponse](./sip.js.incomingcancelresponse.md) | Incoming CANCEL response. |
|  [IncomingInfoRequest](./sip.js.incominginforequest.md) | Incoming INFO request. |
|  [IncomingInfoResponse](./sip.js.incominginforesponse.md) | Incoming INFO response. |
|  [IncomingInviteRequest](./sip.js.incominginviterequest.md) | Incoming INVITE request. |
|  [IncomingMessageRequest](./sip.js.incomingmessagerequest.md) | Incoming MESSAGE request. |
|  [IncomingMessageResponse](./sip.js.incomingmessageresponse.md) | Incoming MESSAGE response. |
|  [IncomingNotifyRequest](./sip.js.incomingnotifyrequest.md) | Incoming NOTIFY request. |
|  [IncomingNotifyResponse](./sip.js.incomingnotifyresponse.md) | Incoming NOTIFY response. |
|  [IncomingPrackRequest](./sip.js.incomingprackrequest.md) | Incoming PRACK request. |
|  [IncomingPrackResponse](./sip.js.incomingprackresponse.md) | Incoming PRACK response. |
|  [IncomingPublishRequest](./sip.js.incomingpublishrequest.md) | Incoming PUBLISH request. |
|  [IncomingPublishResponse](./sip.js.incomingpublishresponse.md) | Incoming PUBLISH response. |
|  [IncomingReferRequest](./sip.js.incomingreferrequest.md) | Incoming REFER request. |
|  [IncomingReferResponse](./sip.js.incomingreferresponse.md) | Incoming REFER response. |
|  [IncomingRegisterRequest](./sip.js.incomingregisterrequest.md) | Incoming REGISTER request. |
|  [IncomingRegisterResponse](./sip.js.incomingregisterresponse.md) | Incoming REGISTER response. |
|  [IncomingRequest](./sip.js.incomingrequest.md) | A SIP message sent from a remote client to a local server. |
|  [IncomingRequestDelegate](./sip.js.incomingrequestdelegate.md) | Delegate providing custom handling of incoming requests. |
|  [IncomingRequestWithSubscription](./sip.js.incomingrequestwithsubscription.md) | Incoming NOTIFY request with associated [Subscription](./sip.js.subscription.md)<!-- -->. |
|  [IncomingResponse](./sip.js.incomingresponse.md) | A SIP message sent from a remote server to a local client. |
|  [IncomingSubscribeRequest](./sip.js.incomingsubscriberequest.md) | Incoming SUBSCRIBE request. |
|  [IncomingSubscribeResponse](./sip.js.incomingsubscriberesponse.md) | Incoming SUBSCRIBE response. |
|  [OutgoingAckRequest](./sip.js.outgoingackrequest.md) | Outgoing ACK request. |
|  [OutgoingByeRequest](./sip.js.outgoingbyerequest.md) | Outgoing BYE request. |
|  [OutgoingCancelRequest](./sip.js.outgoingcancelrequest.md) | Outgoing CANCEL request. |
|  [OutgoingInfoRequest](./sip.js.outgoinginforequest.md) | Outgoing INFO request. |
|  [OutgoingInviteRequest](./sip.js.outgoinginviterequest.md) | Outgoing INVITE request. |
|  [OutgoingInviteRequestDelegate](./sip.js.outgoinginviterequestdelegate.md) | Delegate providing custom handling of outgoing INVITE requests. |
|  [OutgoingMessageRequest](./sip.js.outgoingmessagerequest.md) | Outgoing MESSAGE request. |
|  [OutgoingNotifyRequest](./sip.js.outgoingnotifyrequest.md) | Outgoing NOTIFY request. |
|  [OutgoingPrackRequest](./sip.js.outgoingprackrequest.md) | Outgoing PRACK request. |
|  [OutgoingPublishRequest](./sip.js.outgoingpublishrequest.md) | Outgoing PUBLISH request. |
|  [OutgoingReferRequest](./sip.js.outgoingreferrequest.md) | Outgoing REFER request. |
|  [OutgoingRegisterRequest](./sip.js.outgoingregisterrequest.md) | Outgoing REGISTER request. |
|  [OutgoingRequest](./sip.js.outgoingrequest.md) | A SIP message sent from a local client to a remote server. |
|  [OutgoingRequestDelegate](./sip.js.outgoingrequestdelegate.md) | Delegate providing custom handling of outgoing requests. |
|  [OutgoingRequestMessageOptions](./sip.js.outgoingrequestmessageoptions.md) | Outgoing request message options. |
|  [OutgoingResponse](./sip.js.outgoingresponse.md) | A SIP message sent from a local server to a remote client. |
|  [OutgoingResponseWithSession](./sip.js.outgoingresponsewithsession.md) | Outgoing INVITE response with the associated [Session](./sip.js.session.md)<!-- -->. |
|  [OutgoingSubscribeRequest](./sip.js.outgoingsubscriberequest.md) | Outgoing SUBSCRIBE request. |
|  [OutgoingSubscribeRequestDelegate](./sip.js.outgoingsubscriberequestdelegate.md) | Delegate providing custom handling of outgoing SUBSCRIBE requests. |
|  [PrackableIncomingResponseWithSession](./sip.js.prackableincomingresponsewithsession.md) | Incoming INVITE response received when request is progressed. |
|  [RequestOptions](./sip.js.requestoptions.md) | Request options bucket. |
|  [ResponseOptions](./sip.js.responseoptions.md) | Response options bucket. |
|  [ServerTransactionUser](./sip.js.servertransactionuser.md) | UAS Core Transaction User. |
|  [Session](./sip.js.session.md) | Session. |
|  [SessionDelegate](./sip.js.sessiondelegate.md) | Session delegate. |
|  [Subscription](./sip.js.subscription.md) | Subscription. |
|  [SubscriptionDelegate](./sip.js.subscriptiondelegate.md) | Subscription delegate. |
|  [TransactionUser](./sip.js.transactionuser.md) | Transaction User (TU). |
|  [UserAgentCoreConfiguration](./sip.js.useragentcoreconfiguration.md) | User Agent Core configuration. |
|  [UserAgentCoreDelegate](./sip.js.useragentcoredelegate.md) | User Agent Core delegate. |

## Variables

|  Variable | Description |
|  --- | --- |
|  [Timers](./sip.js.timers.md) | Timers. |
