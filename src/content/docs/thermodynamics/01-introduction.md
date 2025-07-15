---
title: Introduction to Thermodynamics
sidebar:
  order: 1
  label: Introduction
slug: thermodynamics/introduction
prev: false
next: true
---

## Ideal gases

Theoretical gases. Composed of randomly moving particles. No inter-molecular forces. Molecules interact with each other and their container only through perfectly elastic collisions. Occupies no space. Zero volume. Massless.

Some real gases demonstrate ideal behavior most closely at high temperatures and low pressures. The exact boundary values depends on the gas and the environment.

At high temperatures, molecular vibrations become high; inter-molecular forces become negligible. At low pressure, the distance between molecules is high. The volume of the gas molecules is low compared to the total volume of the container.

The behavior of ideal gases is described by the ideal gas law:

```math
PV = mRT
```

Here:
- $P$ - Pressure
- $V$ - Volume
- $m$ - Mass of the gas
- $R$ - Gas constant
- $T$ - Temperature

:::note

Any relation between pressure, volume and temperature is called "equation of state".

:::

```math
R = \frac{R_u}{M}
```

Here:
- $R_u$ - Universal gas constant
- $M$ - Molar mass of the gas

## Specific heat capacity

For reversible processes: The amount of heat required to raise the temperature of unit mass of a substance by one degree Celsius or one Kelvin. Measured in $J/kg/K$. $ $

:::note

A reversible process is one that can be reversed such that the system and the surroundings revert back to the initial state.

:::

For gases, the temperature can be increased in two different ways:
- At constant volume ($C_v$)
- At constant pressure ($C_p$)

## Specific heat capacity at constant volume

The amount of heat required to raise the temperature of unit mass of a substance by one degree Celsius or one Kelvin while keeping the volume constant. Rigid container is used. Work transfer is 0.

```math
\Delta U = \Delta Q = m C_v \Delta T
```

From this equation:

```math
u = C_v T
```

Here:
- $C_v$ - Specific heat capacity at constant volume
- $T$ - Temperature
- $u$ - Specific internal energy

The above equation is an equation of point functions and can be used for any processes.

## Enthalpy

```math
h = u + Pv
```

## Specific heat capacity at constant pressure

The amount of heat required to raise the temperature of unit mass of a substance by one degree Celsius or one Kelvin while keeping the pressure constant. Piston cylinder is used.

```math
\Delta Q - \Delta W = \Delta U
```

```math
m C_p \Delta T - P \Delta V = \Delta U
```

```math
\Delta h = C_p \Delta T
```

```math
h = C_p T
```

Here:
- $C_p$ - Specific heat capacity at constant pressure
- $P$ - Pressure
- $h$ - Specific enthalpy

The above equation is an equation of point functions and can be used for any processes.

:::note

For any gases:
```math
C_p \gt C_v
```

At constant pressure, the given heat is also used to raise the piston against atmospheric pressure. Because of that, $C_p$ is larger. $ $

For ideal gases:
```math
C_p = C_v + R
```

:::

## Specific heat capacity ratio

```math
\gamma = \frac{C_p}{C_v}
```

For diatomic gases: $\gamma = 1.4$. $ $
