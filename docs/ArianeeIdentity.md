# Arianee Identity Schema

```
https://cert.arianee.org/version1/ArianeeIdentity.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                   |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [ArianeeIdentity.json](ArianeeIdentity.json) |

# Arianee Identity Properties

| Property                              | Type       | Required     | Nullable | Default                                                    | Defined by                     |
| ------------------------------------- | ---------- | ------------ | -------- | ---------------------------------------------------------- | ------------------------------ |
| [\$schema](#schema)                   | `string`   | **Required** | No       | `"https://cert.arianee.org/version1/ArianeeIdentity.json"` | Arianee Identity (this schema) |
| [address](#address)                   | `object`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [arianee_member](#arianee_member)     | `boolean`  | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [brandLogoHeader](#brandlogoheader)   | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [brandLogoSquare](#brandlogosquare)   | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [certificate_uri](#certificate_uri)   | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [contacts](#contacts)                 | `object[]` | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [externalContents](#externalcontents) | `object[]` | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [inAppHTML](#inapphtml)               | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [mother_company](#mother_company)     | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [name](#name)                         | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [socialmedia](#socialmedia)           | `object`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| [website](#website)                   | `string`   | Optional     | No       |                                                            | Arianee Identity (this schema) |
| `*`                                   | any        | Additional   | Yes      | this schema _allows_ additional properties                 |

## \$schema

### \$schema

`$schema`

- is **required**
- type: `string`
- default: `"https://cert.arianee.org/version1/ArianeeIdentity.json"`
- defined in this schema

### \$schema Type

`string`

## address

### Address

`address`

- is optional
- type: `object`
- defined in this schema

### address Type

`object` with following properties:

| Property         | Type   | Required     |
| ---------------- | ------ | ------------ |
| `city`           | string | **Required** |
| `country`        | string | **Required** |
| `state`          | string | **Required** |
| `street_address` | string | **Required** |
| `zipcode`        | string | **Required** |

#### city

##### City

`city`

- is **required**
- type: `string`

##### city Type

`string`

#### country

##### Country

`country`

- is **required**
- type: `string`

##### country Type

`string`

#### state

##### State

`state`

- is **required**
- type: `string`

##### state Type

`string`

#### street_address

##### Street Address

`street_address`

- is **required**
- type: `string`

##### street_address Type

`string`

#### zipcode

##### Zip Code

`zipcode`

- is **required**
- type: `string`

##### zipcode Type

`string`

## arianee_member

### Arianee Member

`arianee_member`

- is optional
- type: `boolean`
- defined in this schema

### arianee_member Type

`boolean`

## brandLogoHeader

### Brand Logo Header

url

`brandLogoHeader`

- is optional
- type: `string`
- defined in this schema

### brandLogoHeader Type

`string`

## brandLogoSquare

### Brand Logo Square

url

`brandLogoSquare`

- is optional
- type: `string`
- defined in this schema

### brandLogoSquare Type

`string`

## certificate_uri

### Certificate URI

`certificate_uri`

- is optional
- type: `string`
- defined in this schema

### certificate_uri Type

`string`

## contacts

### Contacts

`contacts`

- is optional
- type: `object[]`
- defined in this schema

### contacts Type

Array type: `object[]`

All items must be of the type: `object` with following properties:

| Property | Type   | Required |
| -------- | ------ | -------- |
| `email`  | string | Optional |
| `name`   | string | Optional |
| `title`  | string | Optional |

#### email

##### Email

`email`

- is optional
- type: `string`

##### email Type

`string`

#### name

##### Name

`name`

- is optional
- type: `string`

##### name Type

`string`

#### title

##### Title

`title`

- is optional
- type: `string`

##### title Type

`string`

## externalContents

### External Contents

`externalContents`

- is optional
- type: `object[]`
- defined in this schema

### externalContents Type

Array type: `object[]`

All items must be of the type: `object` with following properties:

| Property          | Type   | Required |
| ----------------- | ------ | -------- |
| `backgroundColor` | string | Optional |
| `color`           | string | Optional |
| `icon`            | string | Optional |
| `title`           | string | Optional |
| `url`             | string | Optional |

#### backgroundColor

##### Background Color

`backgroundColor`

- is optional
- type: `string`

##### backgroundColor Type

`string`

#### color

##### Color

`color`

- is optional
- type: `string`

##### color Type

`string`

#### icon

##### Icon

URL

`icon`

- is optional
- type: `string`

##### icon Type

`string`

#### title

##### Title

`title`

- is optional
- type: `string`

##### title Type

`string`

#### url

##### Url

`url`

- is optional
- type: `string`

##### url Type

`string`

## inAppHTML

### in App HTML

`inAppHTML`

- is optional
- type: `string`
- defined in this schema

### inAppHTML Type

`string`

## mother_company

### Mother Company

`mother_company`

- is optional
- type: `string`
- defined in this schema

### mother_company Type

`string`

## name

### Name

`name`

- is optional
- type: `string`
- defined in this schema

### name Type

`string`

## socialmedia

### Social Media

`socialmedia`

- is optional
- type: `object`
- defined in this schema

### socialmedia Type

`object` with following properties:

| Property    | Type   | Required |
| ----------- | ------ | -------- |
| `facebook`  | string | Optional |
| `instagram` | string | Optional |
| `twitter`   | string | Optional |

#### facebook

##### Facebook

Facebook Page Id

`facebook`

- is optional
- type: `string`

##### facebook Type

`string`

- minimum length: 2 characters
- maximum length: 80 characters

#### instagram

##### Instagram

account

`instagram`

- is optional
- type: `string`

##### instagram Type

`string`

- minimum length: 2 characters
- maximum length: 80 characters

#### twitter

##### Twitter

account

`twitter`

- is optional
- type: `string`

##### twitter Type

`string`

- minimum length: 2 characters
- maximum length: 80 characters

## website

### Website

`website`

- is optional
- type: `string`
- defined in this schema

### website Type

`string`
