# Interface: CompactVerifyGetKey

## Callable

### CompactVerifyGetKey

▸ **CompactVerifyGetKey**(`protectedHeader`, `token`): [`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array` \| `Promise`<[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array`\>

Interface for Compact JWS Verification dynamic key resolution.
No token components have been verified at the time of this function call.

See [createRemoteJWKSet](../functions/jwks_remote.createRemoteJWKSet.md#function-createremotejwkset)
to verify using a remote JSON Web Key Set.

#### Parameters

| Name | Type |
| :------ | :------ |
| `protectedHeader` | [`CompactJWSHeaderParameters`](types.CompactJWSHeaderParameters.md) |
| `token` | [`FlattenedJWSInput`](types.FlattenedJWSInput.md) |

#### Returns

[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array` \| `Promise`<[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array`\>
