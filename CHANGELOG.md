## 0.7.0

 - Bump minimum ansible version to 2.5 and update ansible syntax.
 - Add supported Ubuntu versions Xenial and Bionic.

## 0.6.2

- Execute JDK post-install script without depending on Ansible handlers.

## 0.6.1

- Run ca-certificates-java postinstall step after OpenJDK is installed.

## 0.6.0

- Remove Jinja2 template delimiters from `when` statements.
- Stop manually installing the JRE. It is automatically installed along with the JDK.

## 0.5.0

- Install OpenJDK 8 via PPA for Ubuntu 14.04

## 0.4.0

- Add Molecule testing support for Ubuntu 16.04

## 0.3.0

- Replace Vagrant example project with Molecule.

## 0.2.6

- Update default Java version.

## 0.2.5

- Update default Java version.

## 0.2.4

- Update default Java version.

## 0.2.3

- Required minimum Ansible version is now 1.8.
- Uses wildcards for package versions.

## 0.2.2

- Add support for 32-bit operating systems.

## 0.2.1

- Add support for supplying a major Java version to install via `java_major_version`.

## 0.2.0

- Add support Oracle Java without breaking backward compatibility.

## 0.1.0

- Initial release.
