
# Email Sent Schema

```
https://ns.adobe.com/xdm/mixins/events/emailsent
```

Use to capture details when sending emails to people.

| [Abstract](../../../../abstract.md) | [Extensible](../../../../extensions.md) | [Status](../../../../status.md) | [Identifiable](../../../../id.md) | [Custom Properties](../../../../extensions.md) | [Additional Properties](../../../../extensions.md) | Defined In |
|-------------------------------------|-----------------------------------------|---------------------------------|-----------------------------------|------------------------------------------------|----------------------------------------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [fieldgroups/experience-event/events/emailsent.schema.json](fieldgroups/experience-event/events/emailsent.schema.json) |

## Email Sent Example
```json
{}
```

# Email Sent Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:directMarketing](#xdmdirectmarketing) | `object` | Optional | Email Sent (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:directMarketing
### Direct marketing

`xdm:directMarketing`
* is optional
* type: `object`
* defined in this schema

### xdm:directMarketing Type


`object` with following properties:


| Property | Type | Required |
|----------|------|----------|
| `xdm:emailSent`| object | Optional |



#### xdm:emailSent
##### Email Sent

undefined

`xdm:emailSent`
* is optional
* type: `object`

##### xdm:emailSent Type

Unknown type `object`.

```json
{
  "title": "Email Sent",
  "type": "object",
  "properties": {
    "xdm:mailingKey": {
      "title": "Mailing Key",
      "description": "Unique composite identifier of the email asset.",
      "$ref": "https://ns.adobe.com/xdm/datatypes/b2b-source"
    },
    "xdm:mailingName": {
      "title": "Mailing Name",
      "type": "string",
      "description": "Name of the email asset."
    },
    "xdm:testVariantID": {
      "title": "Test Variant ID",
      "type": "string",
      "description": "Unique ID of the test variant of the email asset."
    },
    "xdm:testVariantName": {
      "title": "Test Variant Name",
      "type": "string",
      "description": "Name of the test variant of the email asset."
    },
    "xdm:automationRunID": {
      "title": "Automation Run ID",
      "type": "string",
      "description": "Unique ID of the automation run."
    }
  },
  "simpletype": "`object`"
}
```









