# ISignature.Verify Method (Byte[], Byte[], Byte[])
 

Verify a pure signature

**Namespace:**&nbsp;<a href="fc4f881f-e121-9cf0-ed49-65bf6b5a005d">PQnet</a><br />**Assembly:**&nbsp;PQnet (in PQnet.dll) Version: 1.0.0+63cbb78a507491a71ebd4891944ebbfe930c1a59

## Syntax

**C#**<br />
``` C#
bool Verify(
	byte[] message,
	byte[] public_key,
	byte[] signature
)
```

**VB**<br />
``` VB
Function Verify ( 
	message As Byte(),
	public_key As Byte(),
	signature As Byte()
) As Boolean
```

<br />

#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br />The message to authenticate</dd><dt>public_key</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br />The public key to use for verification</dd><dt>signature</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br />The message signature</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a><br />`true` if the signature is valid and the message authentic, `false` otherwise

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.security.cryptography.cryptographicexception" target="_blank" rel="noopener noreferrer">CryptographicException</a></td><td>Public key length did not match the required <a href="41da6bac-6275-ff52-30e3-c22e03bfc6a0">PublicKeyBytes</a></td></tr></table>

## See Also


#### Reference
<a href="4b80cef4-24a0-c733-a838-392068369ad7">ISignature Interface</a><br /><a href="82739381-d6de-13a3-d380-27979193591d">Verify Overload</a><br /><a href="fc4f881f-e121-9cf0-ed49-65bf6b5a005d">PQnet Namespace</a><br />