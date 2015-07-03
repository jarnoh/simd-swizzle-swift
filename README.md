# simd-swizzle-swift

Extension library for Swift 2.0 simd types providing swizzle properties

``` swift
let p = float3(1,2,3);
print(p.xy); // float2(1.0, 2.0)
print(p.yyxz); // float4(2.0, 2.0, 1.0, 3.0)
```

