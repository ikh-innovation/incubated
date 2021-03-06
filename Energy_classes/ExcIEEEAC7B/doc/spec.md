# ExcIEEEAC7B
type: "object"
description : >
## Description
The class represents IEEE Std 421.5-2005 type AC7B model. The model represents excitation systems which consist of an ac alternator with either stationary or rotating rectifiers to produce the dc field requirements. It is an upgrade to earlier ac excitation systems, which replace only the controls but retain the ac alternator and diode rectifier bridge.  Reference: IEEE Standard 421.5-2005 Section 6.7.  In the IEEE Standard 421.5 - 2005, the [1 / sT] block is shown as [1 / (1 + sT)], which is incorrect.

## Data Model
  - properties:
    - kpr:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator proportional gain (K).  Typical Value = 4.24. Default: 0.0
    - kir:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator integral gain (K).  Typical Value = 4.24. Default: 0.0
    - kdr:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator derivative gain (K).  Typical Value = 0. Default: 0.0
    - tdr:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lag time constant (T).  Typical Value = 0. Default: 0
    - vrmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum voltage regulator output (V).  Typical Value = 5.79. Default: 0.0
    - vrmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum voltage regulator output (V).  Typical Value = -5.79. Default: 0.0
    - kpa:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator proportional gain (K).  Typical Value = 65.36. Default: 0.0
    - kia:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator integral gain (K).  Typical Value = 59.69. Default: 0.0
    - vamax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum voltage regulator output (V).  Typical Value = 1. Default: 0.0
    - vamin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum voltage regulator output (V).  Typical Value = -0.95. Default: 0.0
    - kp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Potential circuit gain coefficient (K).  Typical Value = 4.96. Default: 0.0
    - kl:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter field voltage lower limit parameter (K).  Typical Value = 10. Default: 0.0
    - te:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter time constant, integration rate associated with exciter control (T).  Typical Value = 1.1. Default: 0
    - vfemax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter field current limit reference (V).  Typical Value = 6.9. Default: 0.0
    - vemin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum exciter voltage output (V).  Typical Value = 0. Default: 0.0
    - ke:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter constant related to self-excited field (K).  Typical Value = 1. Default: 0.0
    - kc:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rectifier loading factor proportional to commutating reactance (K). Typical Value = 0.18. Default: 0.0
    - kd:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Demagnetizing factor, a function of exciter alternator reactances (K).  Typical Value = 0.02. Default: 0.0
    - kf1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer gain (K).  Typical Value = 0.212. Default: 0.0
    - kf2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0
    - kf3:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0
    - tf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer time constant (T).  Typical Value = 1. Default: 0
    - ve1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter alternator output voltages back of commutating reactance at which saturation is defined (V) equals V (V).  Typical Value = 6.3. Default: 0.0
    - seve1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.44. Default: 0.0
    - ve2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter alternator output voltages back of commutating reactance at which saturation is defined (V).  Typical Value = 3.02. Default: 0.0
    - seve2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.075. Default: 0.0
