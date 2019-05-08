# ![LOGO](logo.png) Twilio **flow**ground Connector

## Description

A generated **flow**ground connector for the Twilio API (version 2010-04-01).

Generated from: https://api.apis.guru/v2/specs/twilio.com/2010-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:44:33+03:00

## API Description

Enabling phones, VoIP, and messaging to be embedded into web, desktop, and mobile software.


## Authorization

Supported authorization schemes:
- Basic Authentication

## Actions

### Delete this application.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ApplicationSid` - _required_

### Get application instance resource.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ApplicationSid` - _required_

### Tries to update the application's properties, and returns the updated<br/>
> resource representation if successful. The returned response is identical<br/>
> to that returned above when making a GET request.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ApplicationSid` - _required_

### Returns a list of Application resource representations, each representing<br/>
> an application within your account. The list includes paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Creates a new application within your account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Get the properties of the authorized application.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ConnectAppSid` - _required_

### Returns a list of Connect App resource representations, each representing a<br/>
> Connect App you've authorized to access your account. The list includes<br/>
> paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of local AvailablePhoneNumber resource representations<br/>
> that match the specified filters, each representing a phone number tha<br/>
> is currently available for provisioning within your account.

#### Input Parameters
* `AccountSid` - _required_
* `IsoCountryCode` - _required_ - ISO 3166-1 alpha-2.
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of mobile AvailablePhoneNumber resource representations that match the specified filters, each representing a phone number that is currently available for provisioning within your account.

#### Input Parameters
* `AccountSid` - _required_
* `IsoCountryCode` - _required_ - ISO 3166-1 alpha-2.
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of toll-free AvailablePhoneNumber elements that match the<br/>
> specified filters, each representing a phone number that is currently<br/>
> available for provisioning within your account. To provision an available<br/>
> phone number, POST the number to the IncomingPhoneNumbers resource.

#### Input Parameters
* `AccountSid` - _required_
* `IsoCountryCode` - _required_ - ISO 3166-1 alpha-2.
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of all AvailablePhoneNumber subresources for your account by ISO Country. For full information about our phone number support, see our Phone Number CSV (http://www.twilio.com/resources/rates/international-phone-number-rates.csv).

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of notifications generated for an account. The list includes<br/>
> paging information.

#### Input Parameters
* `AccountSid` - _required_
* `CallSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of Recording resource representations, each representing a<br/>
> recording generated during the course of a phone call.

#### Input Parameters
* `AccountSid` - _required_
* `CallSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns the single Call resource identified by {CallSid}.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Modify a phone call.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Returns a list of phone calls made to and from the account identified by {AccountSid}.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### To make a call, make an HTTP POST request. Initiate a new phone call.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Kick this participant from the conference.

#### Input Parameters
* `AccountSid` - _required_
* `ConferenceSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Returns a representation of this participant.

#### Input Parameters
* `AccountSid` - _required_
* `ConferenceSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Updates the status of a participant.

#### Input Parameters
* `AccountSid` - _required_
* `ConferenceSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Returns the list of participants in the conference identified by<br/>
> {ConferenceSid}.

#### Input Parameters
* `AccountSid` - _required_
* `ConferenceSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a representation of the conference identified by {ConferenceSid}.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ConferenceSid` - _required_

### Returns a list of conferences within an account. The list includes paging<br/>
> information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Get the properties of a Connect App.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ConnectAppSid` - _required_

### Tries to update the Connect App's properties, and returns the updated<br/>
> resource representation if successful. The returned response is identical<br/>
> to that returned above when making a GET request.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ConnectAppSid` - _required_

### Returns a list of Connect App resource representations, each representing<br/>
> a Connect App in your account. The list includes paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a list of local <IncomingPhoneNumber> elements, each representing a local (not toll-free) phone number given to your account, under an <IncomingPhoneNumbers> list element that includes paging information. Works exactly the same as the IncomingPhoneNumber resource, but filters out toll-free numbers.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Adds a new phone number to your account. If a phone number is found for your request, Twilio will add it to your account and bill you for the first month's cost of the phone number.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Returns a list of local <IncomingPhoneNumber> elements, each representing a mobile phone number given to your account, under an <IncomingPhoneNumbers> list element that includes paging information. Works exactly the same as the IncomingPhoneNumber resource, but filters out local and toll free numbers.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Adds a new phone number to your account. If a phone number is found for your request, Twilio will add it to your account and bill you for the first month's cost of the phone number.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Returns a list of local <IncomingPhoneNumber> elements, each representing a toll-free phone number given to your account, under an <IncomingPhoneNumbers> list element that includes paging information. Works exactly the same as the IncomingPhoneNumber resource, but filters out all numbers that aren't toll-free.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Adds a new phone number to your account. If a phone number is found for your request, Twilio will add it to your account and bill you for the first month's cost of the phone number.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Release this phone number from your account. Twilio will no longer answer<br/>
> calls to this number, and you will stop being billed the monthly phone<br/>
> number fee. The phone number will eventually be recycled and potentially<br/>
> given to another customer, so use with care. If you make a mistake, contac<br/>
> us. We may be able to give you the number back.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IncomingPhoneNumberSid` - _required_

### Get info about incoming call's phone number.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IncomingPhoneNumberSid` - _required_

### Tries to update the incoming phone number's properties, and returns the<br/>
> updated resource representation if successful. The returned response is<br/>
> identical to that returned above when making a GET request.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IncomingPhoneNumberSid` - _required_

### Tries to update the incoming phone number's properties, and returns the<br/>
> updated resource representation if successful. The returned response is<br/>
> identical to that returned above when making a GET request.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IncomingPhoneNumberSid` - _required_

### Returns a list of IncomingPhoneNumber resource representations, each<br/>
> representing a phone number given to your account. The list includes paging<br/>
> information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Purchases a new phone number for your account. If a phone number is found<br/>
> for your request, Twilio will add it to your account and bill you for the<br/>
> first month's cost of the phone number.<br/>
> To find an available phone number to POST, use the subresources of the<br/>
> AvailablePhoneNumbers list resource.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Without an extension, the media is returned using the mime-type provided when the media was generated.

#### Input Parameters
* `AccountSid` - _required_
* `MessageSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `MediaSid` - _required_

### Returns a list of media associated with your message.

#### Input Parameters
* `AccountSid` - _required_
* `MessageSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a single message specified by the provided {MessageSid}.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `MessageSid` - _required_

### Returns a list of messages associated with your account. The list includes paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### To send a new outgoing message, make an HTTP POST to your Messages list resource URI

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Deletes the notification identified by {NotificationSid} from an account's log.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `NotificationSid` - _required_

### Get a notification entry.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `NotificationSid` - _required_

### Returns a list of notifications generated for an account. The list includes<br/>
> paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Deletes the caller ID from the account. Returns an HTTP 204 response if<br/>
> successful, with no body.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `OutgoingCallerIdSid` - _required_

### Get the set of an account's verified phone numbers.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `OutgoingCallerIdSid` - _required_

### Updates the caller id, and returns the updated resource if successful.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `OutgoingCallerIdSid` - _required_

### Updates the caller id, and returns the updated resource if successful.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `OutgoingCallerIdSid` - _required_

### Returns a list of OutgoingCallerId resource representations, each representing<br/>
> a Caller ID number valid for an account. The list includes paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Adds a new CallerID to your account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Get a front member.

#### Input Parameters
* `AccountSid` - _required_
* `QueueSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Posting a URL and Method to a Queue instance will dequeue a member from a<br/>
> queue and have the member's call begin executing the TwiML document at that URL<br/>
> When dequeuing the 'Front' of the queue, the next call in the queue will be redirected.

#### Input Parameters
* `AccountSid` - _required_
* `QueueSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Get a specific member.

#### Input Parameters
* `AccountSid` - _required_
* `QueueSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Posting a URL and Method to a Queue instance will dequeue a member from a<br/>
> queue and have the member's call begin executing the TwiML document at that URL<br/>
> When redirecting a member of a queue addressed by CallSid, only the first request<br/>
> will succeed and return a 200 response code. A second request will fail and<br/>
> return an appropriate 400 response code.

#### Input Parameters
* `AccountSid` - _required_
* `QueueSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CallSid` - _required_

### Returns the list of members in the queue identified by {QueueSid}.

#### Input Parameters
* `AccountSid` - _required_
* `QueueSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### The DELETE method allows you to remove a Queue. Only empty queues are<br/>
> deletable.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `QueueSid` - _required_

### Get resource's individual Queue instance.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `QueueSid` - _required_

### This POST request allows you to change the FriendlyName or MaxSize.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `QueueSid` - _required_

### Returns a list of queues within an account. The list includes paging<br/>
> information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Create a new Queue resource.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a set of Transcription resource representations that includes paging<br/>
> information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `RecordingSid` - _required_

### Deletes a recording  from your account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .xml, .wav, .mp3.
* `RecordingSid` - _required_

### Returns one of several representations:<br/>
> Without an extension, or with a ".wav", a binary WAV audio file is returned<br/>
> with mime-type "audio/x-wav".<br/>
> Appending ".mp3" to the URI returns a binary MP3 audio file with mime-type<br/>
> type "audio/mpeg".<br/>
> Appending ".xml" to the URI returns a XML representation.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .xml, .wav, .mp3.
* `RecordingSid` - _required_

### Returns a list of Recording resource representations, each representing a<br/>
> recording generated during the course of a phone call.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Remove a Credential from a CredentialList.

#### Input Parameters
* `AccountSid` - _required_
* `CLSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CredentialSid` - _required_

### Get a specific Credential in a list. Though a password is stored for each username in your list, the password is not returned to protect your password. If you cannot remember your password, you will need to POST to this resource to update it.

#### Input Parameters
* `AccountSid` - _required_
* `CLSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CredentialSid` - _required_

### Change the password of a Credential record.<br/>
> <br/>
> If the change is successful, Twilio will respond with the Credential record but will not include the password in the response.

#### Input Parameters
* `AccountSid` - _required_
* `CLSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CredentialSid` - _required_

### Get the list of Credentials in a CredentialList. The passwords for the Credentials are intentionally not returned so as to protect them.

#### Input Parameters
* `AccountSid` - _required_
* `CLSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Add a Credential to the CredentialList.<br/>
> <br/>
> When creating a Credential, you will POST both a username and password, but only receive the username back in the response. The password is intentionally not returned so as to protect it.

#### Input Parameters
* `AccountSid` - _required_
* `CLSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Delete a CredentialList from your account. It can only be deleted if no domains are mapped to it. If you attempt to delete one that is mapped to a domain, you will receive an error.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CLSid` - _required_

### Get a credential list instance resource

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CLSid` - _required_

### Change the FriendlyName of the list

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CLSid` - _required_

### Gets a list of Credential Lists for an account

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Create a new Credential List.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Remove a CredentialListMapping from a domain

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `CLSid` - _required_

### Get the user lists mapped to this domain.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Map a CredentialList to the domain.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Remove a mapping from this domain.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ALSid` - _required_

### Return a specific IpAccessControlListMapping instance by Sid.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ALSid` - _required_

### Return the IpAccessControlListMappings that are associated to this domain.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_

### Map an IpAccessControlList to this domain.

#### Input Parameters
* `AccountSid` - _required_
* `SipDomainSid` - _required_
* `mediaTypeExtension` - _required_

### Delete a domain. If you have created subdomains of a domain, you will not be able to delete the domain until you first delete all subdomains of it.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `SipDomainSid` - _required_

### Return a specific instance by Sid.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `SipDomainSid` - _required_

### Update the attributes of a domain.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `SipDomainSid` - _required_

### Returns a paged list of the domains for an account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Creates a new Domain and returns its instance resource. You must pick a unique domain name that ends in ".sip.twilio.com".<br/>
> After creating a Domain, you must map it to an authentication method before the domain is ready to receive traffic.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Deletes an IP address entry from the list.

#### Input Parameters
* `AccountSid` - _required_
* `IpAccessControlListSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAddressSid` - _required_

### Return a single IP Address resource.

#### Input Parameters
* `AccountSid` - _required_
* `IpAccessControlListSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAddressSid` - _required_

### Change the description or IP address of a given IpAddress instance resource

#### Input Parameters
* `AccountSid` - _required_
* `IpAccessControlListSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAddressSid` - _required_

### List the IP Addresses contained in this list.

#### Input Parameters
* `AccountSid` - _required_
* `IpAccessControlListSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Add an IP Address to the list with a description.

#### Input Parameters
* `AccountSid` - _required_
* `IpAccessControlListSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Delete an IpAccessControlList from your account. It can only be deleted if no domains are mapped to it. If you attempt to delete one that is mapped to a domain, you will receive an error.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAccessControlListSid` - _required_

### Return a specific IpAccessControlList resource.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAccessControlListSid` - _required_

### Rename an IpAccessControlList.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `IpAccessControlListSid` - _required_

### Return a paged list of all IpAccessControlLists under this account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Create a new IpAccessControlList resource.<br/>
> <br/>
> When created, the list will contain no IP addresses. You will need to add IP addresses to the list for it to be active. To add IP addresses, you will need to POST to the IpAddresses List subresource.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_

### Get a single message.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ShortCodeSid` - _required_

### Tries to update the shortcode's properties, and returns the updated<br/>
> resource representation if successful.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `ShortCodeSid` - _required_

### Returns a list of ShortCode resource representations, each representing a<br/>
> short code within your account. The list includes paging information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Deletes a transcription from your account.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .json, .csv, .html, .txt, .xml.
* `TranscriptionSid` - _required_

### Returns a single Transcription resource representation identified by the<br/>
> given {TranscriptionSid}. By default Twilio will respond with the XML metadata for the Transcription. If you append ".txt" to the end of the Transcription resource's URI Twilio will just return you the transcription tex.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .json, .csv, .html, .txt, .xml.
* `TranscriptionSid` - _required_

### Returns a set of Transcription resource representations that includes paging<br/>
> information.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns UsageRecords for all usage categories for a specified period.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `Subresource` - _required_ - |Subresource|Description|
|---|---|
|Daily|Return multiple UsageRecords for each usage category, each representing usage over a daily time-interval.|
|Monthly|Return multiple UsageRecords for each usage category, each representing usage over a monthly time-interval.|
|Yearly|Return multple UsageRecords for each usage category, each representing usage over a yearly time-interval.|
|AllTime|  Return a single UsageRecord for each usage category, each representing usage over the date-range specified. This is the same as the root /Usage/Records.|
|Today|Return a single UsageRecord per usage category, for today's usage only.|
||Yesterday|Return a single UsageRecord per usage category, for yesterday's usage only.|
|ThisMonth|Return a single UsageRecord per usage category, for this month's usage only.|
|LastMonth|Return a single UsageRecord per usage category, for last month's usage only.|

    Possible values: Daily, Monthly, Yearly, AllTime, Today, Yesterday, ThisMonth, LastMonth.

### Returns UsageRecords for all usage categories. The list includes paging<br/>
> information.<br/>
> By default, the UsageRecords resource will return one UsageRecord for<br/>
> each Category, representing all usage accrued all-time for the account.<br/>
> You can filter the usage Category or change the date-range over which usage<br/>
> is counted using optional GET query parameters.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Delete this UsageTrigger.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `UsageTriggerSid` - _required_

### Returns a repesentation of the UsageTrigger.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `UsageTriggerSid` - _required_

### Tries to update the UsageTrigger's properties, and returns the updated<br/>
> resource representation if successful.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `UsageTriggerSid` - _required_

### Returns a list of UsageTrigger resource representations. The list includes<br/>
> paging information.<br/>
> By default, all UsageTriggers are returned. You can filter the list by<br/>
> specifying one or more query parameters. Note that the query parameters are<br/>
> case-sensitive

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Creates a new UsageTrigger. Each account can create up to 1,000 UsageTriggers.<br/>
> Currently, UsageTriggers that are no longer active are not deleted automatically.<br/>
> Use DELETE to delete triggers you no longer need.

#### Input Parameters
* `AccountSid` - _required_
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Returns a representation of an account.

#### Input Parameters
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `AccountSid` - _required_ - A 34 character string that uniquely identifies this account.

### Allows you to modify the properties of an account.

#### Input Parameters
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `AccountSid` - _required_ - A 34 character string that uniquely identifies this account.

### Allows you to modify the properties of an account.

#### Input Parameters
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.
* `AccountSid` - _required_ - A 34 character string that uniquely identifies this account.

### Retrieve a list of the Account resources belonging to the account used to make the<br/>
> API request. This list will include that Account as well.

#### Input Parameters
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

### Create a new Account instance resource as a subaccount of the one used to make the request. See<br/>
> Creating Subaccounts for more information.

#### Input Parameters
* `mediaTypeExtension` - _required_ - By default, Twilio's REST API returns XML. You may obtain CSV, JSON or HTML by appending ".csv", ".json", or ".html".

    Possible values: .xml, .json, .csv, .html.

## License

**flow**ground :- Telekom iPaaS / twilio-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
