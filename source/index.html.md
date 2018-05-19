---

title: dev-EverydayAI-API

language_tabs:
   - shell

toc_footers:
   - <a href='#'>Sign Up for a Developer Key</a>
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a>

includes:
   - errors

search: true

---

# Introduction

**Version:** 2018-05-19T23:45:53Z

# /BRAINS
## ***GET***

### HTTP Request
`***GET*** /brains`

**Responses**

| Code | Description |
| ---- | ----------- |

## ***POST***

### HTTP Request
`***POST*** /brains`

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | query |  | Yes | string |
| data | query |  | No | string |
| schema | query |  | No | string |

**Responses**

| Code | Description |
| ---- | ----------- |

## ***OPTIONS***

### HTTP Request
`***OPTIONS*** /brains`

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | 200 response |

# /BRAINS/{ID}
## ***GET***

### HTTP Request
`***GET*** /brains/{id}`

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |

## ***PUT***

### HTTP Request
`***PUT*** /brains/{id}`

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | query |  | No | string |
| data | query |  | No | string |
| schema | query |  | No | string |
| id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |

## ***DELETE***

### HTTP Request
`***DELETE*** /brains/{id}`

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |

## ***OPTIONS***

### HTTP Request
`***OPTIONS*** /brains/{id}`

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | 200 response |

# /TESTS
## ***GET***

### HTTP Request
`***GET*** /tests`

**Responses**

| Code | Description |
| ---- | ----------- |

## ***POST***

### HTTP Request
`***POST*** /tests`

**Responses**

| Code | Description |
| ---- | ----------- |

## ***OPTIONS***

### HTTP Request
`***OPTIONS*** /tests`

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | 200 response |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
