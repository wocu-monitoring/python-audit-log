
## [unreleased - 03-12-2021]
- Allow `username` logging when user is authenticated

## 0.4.0 (20-10-2020)

### Note worthy changes
- Don't pin dependencies
- Dropped 3.5 support, added 3.9
- Use python 3.9 buster-minimal base image
- Added github CI workflow
- Run tox inside docker using pyenv for versions

### Backwards incompatible changes
- None


## 0.3.1 (20-01-2020)

### Note worthy changes
- Prevent duplicate log handlers for the audit log

### Backwards incompatible changes
- None


## 0.3.0 (20-12-2019)

### Note worthy changes
- Made AuditLogger more configurable
- Raise test coverage for formatter
- Added requirements files useful while developing

### Backwards incompatible changes
- None


## 0.2.1 (31-10-2019)

### Note worthy changes
- New version because I deleted 0.2.0 and pypi doesn't want to reuse the version.

### Backwards incompatible changes
- None


## 0.2.0 (31-10-2019)

### Note worthy changes
- Implemented prepare release commands (PR #2)
- Allow to set filter kwargs to be more generic (PR #1)

### Backwards incompatible changes
- AuditLogger.filter() signature changed to filter(object_name: str, kwargs: dict). 
See https://github.com/Amsterdam/python-audit-log/commit/8a4daf8a04d55cc9adc7c5283b3633fc4ef43b2f


## 0.1.1 (28-10-2019)

### Note worthy changes
- README improvement

### Backwards incompatible changes
- None 


## 0.1.0 (28-10-2019)

### Note worthy changes
- Initial release.

### Backwards incompatible changes
- None 
