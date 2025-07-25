# foamSite
Aalto OpenFOAM `$WM_PROJECT_SITE`.

## Usage
0. Clone repo:
```sh
git clone git@github.com:Aalto-CFD/foamSite.git /scratch/eng/t21206-cfd/share/site
```
1. Export path to this folder _before_ sourcing OpenFOAM, e.g.:
```sh
export WM_PROJECT_SITE=/scratch/eng/t21206-cfd/share/site
```
2. Source OpenFOAM
3. Compile
```sh
wmake -all $WM_PROJECT_SITE
```
