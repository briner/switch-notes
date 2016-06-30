# IDP
## OpenID connect Pilot
by Michael Hausherr & Dominik Huber @ FNHW

OIDC allow single sing-on for consumers + API acces
Token format: json

Implementation:
 - IdentityServer3
 - Kentor Authentication Services
  - allow relation with saml (IdP)

info:
 - attributes in SAML are claims in OIDC
 - scope is a way to encapsulate a set of attributes
 - you can ask/register an application to have mulitple scopes ()

## OIDC for swiss edu-ID
by Étienne Dysli-Metref @ Switch
  - open for tester (drop an email to Etienne)
  - it exists a Working Group REFEDS OIDCre
  - possibility for an OpenID Connect Federation

## AAI & SAP SAML2 for Fiori
by Daniel Emch @ UZH
 - sounds that it works only for web service (normal this is web based SSO)
 -

## Multi-Factor Authentication Pilot Update
by Étienne Dysli-Metref @ Switch
 - stuff that we do in Geneva
 - [IDP 962](https://issues.shibboleth.net/jira/browse/IDP-962)

## SAML Attribute Query
by Lukas Hämmerle @ Switch
 - needed for Swiss edu-ID
 - accessible by /Shibboleth.sso/AttributeQuery?nameID=XY
 - There is a [test](http://av.aai.switch.ch/aai/attribute-query-test) hosted on switch to know if our IdP is compatible
  - Succeeded

## Single Logout with IdPv3
by Étiene Dysli-Metref @ Switch

(nothing)

## SIRTFI Security Contact Intro
by Thomas Bärecke @ Switch

Or how to handle compromised AAI IdP: as the federation and interfederation gives a user the ability to go to many websites, the idea is how we handle the case when we know that an accoount as been compromised.

The presentation was mainly about:
 - you must reply
 - your must keep user privacy
 - you must apply to the organisation to not communicate if asked

## Attribute Releas Update
by Lukas Hämmerle @ Switch
 - no release anymore of shac* attirbute
 - go from nothing, minimal, full to nothing, full
 - move from transient ID to persistent ID in the SAML attribute

# Swiss Edu ID
## general presentation
(nothing)

##Pilot Projects
###Registration portal with Evento
by Franz Peter Süss @ ZHAW & Michael Hausherr @ FNHW
