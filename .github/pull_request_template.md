### If this is a Pull Request for MaGe macro files:
* have you tested the macro files in your cluster?
* have you run `julia UTILS/health-dep/mac-doctor.jl`
* have you updated the number of primaries (and the contact) in `volume/part/metadata.json`?
* have you filled the volume description (if you are adding a volume) in `volume/metadata.json`?
* have you run `julia UTILS/health-dep/meta-doctor.jl`?

### If this is a Pull Request for the software:
* have you documented your changes in `UTILS/README.md`?
