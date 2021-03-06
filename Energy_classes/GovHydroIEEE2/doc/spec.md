# GovHydroIEEE2
type: "object"
description : >
## Description
IEEE hydro turbine governor model represents plants with straightforward penstock configurations and hydraulic-dashpot governors.  Ref

## Data Model
  - properties:
    - mwbase:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Base for power values (MWbase) (> 0).  Unit = MW. Default: 0.0
    - tg:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Gate servo time constant (Tg).  Typical Value = 0.5. Default: 0
    - tp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Pilot servo valve time constant (Tp).  Typical Value = 0.03. Default: 0
    - uo:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum gate opening velocity (Uo). Unit = PU/sec.  Typical Value = 0.1. Default: 0.0
    - uc:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum gate closing velocity (Uc) (<0).  Typical Value = -0.1. Default: 0.0
    - pmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum gate opening (Pmax).  Typical Value = 1. Default: 0.0
    - pmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum gate opening (Pmin).  Typical Value = 0. Default: 0.0
    - rperm:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Permanent droop (Rperm).  Typical Value = 0.05. Default: 0.0
    - rtemp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Temporary droop (Rtemp).  Typical Value = 0.5. Default: 0.0
    - tr:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Dashpot time constant (Tr).  Typical Value = 12. Default: 0
    - tw:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Water inertia time constant (Tw).  Typical Value = 2. Default: 0
    - kturb:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Turbine gain (Kturb).  Typical Value = 1. Default: 0.0
    - aturb:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Turbine numerator multiplier (Aturb).  Typical Value = -1. Default: 0.0
    - bturb:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Turbine denominator multiplier (Bturb).  Typical Value = 0.5. Default: 0.0
    - gv1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 1, PU gv (Gv1).  Typical Value = 0. Default: 0.0
    - pgv1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 1, PU power (Pgv1).  Typical Value = 0. Default: 0.0
    - gv2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 2, PU gv (Gv2).  Typical Value = 0. Default: 0.0
    - pgv2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 2, PU power (Pgv2).  Typical Value = 0. Default: 0.0
    - gv3:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 3, PU gv (Gv3).  Typical Value = 0. Default: 0.0
    - pgv3:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 3, PU power (Pgv3).  Typical Value = 0. Default: 0.0
    - gv4:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 4, PU gv (Gv4).  Typical Value = 0. Default: 0.0
    - pgv4:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 4, PU power (Pgv4).  Typical Value = 0. Default: 0.0
    - gv5:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 5, PU gv (Gv5).  Typical Value = 0. Default: 0.0
    - pgv5:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 5, PU power (Pgv5).  Typical Value = 0. Default: 0.0
    - gv6:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 6, PU gv (Gv6).  Typical Value = 0. Default: 0.0
    - pgv6:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Nonlinear gain point 6, PU power (Pgv6).  Typical Value = 0. Default: 0.0
