# ![LOGO](logo.png) WordNet APIs **flow**ground Connector

## Description

A generated **flow**ground connector for the WordNet APIs API (version 0.0.1).

Generated from: https://api.apis.guru/v2/specs/apitore.com/wordnetApis/0.0.1/swagger.json<br/>
Generated at: 2019-05-07T17:36:53+03:00

## API Description

You can access ALL WordNet DB.<BR />[Endpoint] https://api.apitore.com/api/46

## Authorization

This API does not require authorization.

## Actions

### WordNet WebAPI. Return Sense object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `synset` - _required_ - Synset
* `lang` - _optional_ - Language. [jpn:japanese,eng:english]

### WordNet WebAPI. Return Sense object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `wordid` - _required_ - Word ID

### WordNet WebAPI. Return SynLink object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `synset` - _required_ - Synset
* `link` - _optional_ - Link. You can specify several link by csv format. [also, syns, hype, inst, hypo, hasi, mero, mmem, msub, mprt, holo, hmem, hsub, hprt, attr, sim, enta, caus, dmnc, dmnu, dmnr, dmtc, dmtu, dmtr, ants]

### WordNet WebAPI. Return Synset object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `name` - _required_ - Name
* `pos` - _required_ - Part-of-speech. [n:noun,v:verb,a:adjective,r:adverb]

### WordNet WebAPI. Return Synset object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `synset` - _required_ - Synset

### WordNet WebAPI. Return SynsetDef object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `synset` - _required_ - Synset
* `lang` - _required_ - Language. [jpn:japanese,eng:english]

### WordNet WebAPI. Return Word object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `lemma` - _required_ - Lemma
* `pos` - _optional_ - Part-of-speech. You can specify several pos by csv format. [n:noun,v:verb,a:adjective,r:adverb]

### WordNet WebAPI. Return Word object.

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />

*Tags:* `wordnet-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `wordid` - _required_ - Word ID

## License

**flow**ground :- Telekom iPaaS / apitore-com-wordnet-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
