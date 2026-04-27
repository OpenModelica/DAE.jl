# DAE.jl

Julia port of the OpenModelica `DAE` module, providing the intermediate
representation used by the OM.jl Modelica compiler stack. It defines the
core uniontypes, records, and constants for differential-algebraic
equations, expressions, components, and types after frontend
instantiation.

DAE.jl is a sibling package of `Absyn`, `SCode`, `MetaModelica`, and
`ImmutableList`, and is consumed by `OMFrontend.jl` and `OMBackend.jl`
during translation from Modelica to executable Julia/MTK code.

## License

Dual-licensed under AGPL-3.0 or the OSMC-PL 1.8. See `LICENSE.md`.
