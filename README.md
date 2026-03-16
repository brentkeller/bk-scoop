# bk-scoop

Brent's custom [Scoop](https://scoop.sh) bucket.

## Usage

```powershell
scoop bucket add bk-scoop https://github.com/brentkeller/bk-scoop
scoop install bk-scoop/<app-name>
```

## New Machine Setup

The included `scoopfile.json` can be used to install all apps at once on a new machine:

```powershell
scoop import scoopfile.json
```

## Updating the Scoopfile

To update `scoopfile.json` with your currently installed apps, run:

```powershell
just export
```
