<p align="center">
<a href="https://www.npmjs.com/package/@taktikorg/unde-animi-omnis"><img src="https://img.shields.io/npm/v/@taktikorg/unde-animi-omnis"></a>
<a href=""><img src="https://img.shields.io/github/actions/workflow/status/RemiMyrset/@taktikorg/unde-animi-omnis/build.yml"></a>
<a href="https://en.wikipedia.org/wiki/MIT_License"><img src="https://img.shields.io/npm/l/@taktikorg/unde-animi-omnis"></a>
<a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/npm/types/@taktikorg/unde-animi-omnis" /></a>
</p>

# Deep Object Mapper

Map different bits from one object to another

Example usage:

```ts
const { 
  output,
} = deepMap<ElectricUpgradeKit, CombustionCar>({
  input,
  map: {
    "kit.engine": "engine",
    "kit.battery": "battery",
    "gizmo": "dashboard.gloveBox"
  },
})
```