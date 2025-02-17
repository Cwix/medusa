# Namespace: "/Users/shahednasser/medusa/packages/medusa/dist/types/global"

[internal](internal-13.md)."/Users/shahednasser/medusa/packages/medusa/dist/types/global"

## Type Aliases

### ClassConstructor

Ƭ **ClassConstructor**<`T`\>: `Object`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Defined in

medusa/dist/types/global.d.ts:27

___

### ConfigModule

Ƭ **ConfigModule**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `featureFlags` | `Record`<`string`, `boolean` \| `string`\> |
| `plugins` | ({ `options`: `Record`<`string`, `unknown`\> ; `resolve`: `string`  } \| `string`)[] |
| `projectConfig` | { `admin_cors?`: `string` ; `cookie_secret?`: `string` ; `database_database?`: `string` ; `database_extra?`: `Record`<`string`, `unknown`\> & { `ssl`: { `rejectUnauthorized`: ``false``  }  } ; `database_logging`: `LoggerOptions` ; `database_type`: `string` ; `database_url?`: `string` ; `jwt_secret?`: `string` ; `redis_url?`: `string` ; `store_cors?`: `string`  } |
| `projectConfig.admin_cors?` | `string` |
| `projectConfig.cookie_secret?` | `string` |
| `projectConfig.database_database?` | `string` |
| `projectConfig.database_extra?` | `Record`<`string`, `unknown`\> & { `ssl`: { `rejectUnauthorized`: ``false``  }  } |
| `projectConfig.database_logging` | `LoggerOptions` |
| `projectConfig.database_type` | `string` |
| `projectConfig.database_url?` | `string` |
| `projectConfig.jwt_secret?` | `string` |
| `projectConfig.redis_url?` | `string` |
| `projectConfig.store_cors?` | `string` |

#### Defined in

medusa/dist/types/global.d.ts:38

___

### ExtendedRequest

Ƭ **ExtendedRequest**<`TEntity`\>: `Request` & { `resource`: `TEntity`  }

#### Type parameters

| Name |
| :------ |
| `TEntity` |

#### Defined in

medusa/dist/types/global.d.ts:24

___

### Logger

Ƭ **Logger**: `_Logger` & { `info`: (`msg`: `string`) => `void` ; `progress`: (`activityId`: `string`, `msg`: `string`) => `void` ; `warn`: (`msg`: `string`) => `void`  }

#### Defined in

medusa/dist/types/global.d.ts:33

___

### MedusaContainer

Ƭ **MedusaContainer**: `AwilixContainer` & { `registerAdd`: <T\>(`name`: `string`, `registration`: `T`) => [`MedusaContainer`](internal-13.__Users_shahednasser_medusa_packages_medusa_dist_types_global_.md#medusacontainer)  }

#### Defined in

medusa/dist/types/global.d.ts:30
