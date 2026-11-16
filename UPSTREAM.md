# Upstream index — aerynOS/os-tools

Beam is a pinned fork of [aerynOS/os-tools](https://github.com/aerynOS/os-tools) (moss + boulder).

- **Fork:** PhilboHackinz/Beam-package-manager
- **Pin at fork:** `d9c7d289c0a9bd65a78fe8c532526cc21afbaaf4` (2026-11-14, workspace v0.26.10)
- **Checked:** 2026-11-16
- **Upstream open at check:** 121 issues, 34 PRs
- **Policy:** This file is the reference index. Do NOT mirror all of these as Beam issues. Copy an upstream item into a Beam issue only when a lane is assigned to work on it, and link back to the upstream number.
- **License:** MPL-2.0 (upstream). Upstream CONTRIBUTING bars genAI/LLM-authored contributions upstream — Beam work stays in this fork.

## Starter issues mirrored into Beam

- Upstream #901 — Running `moss ste | false` leads to a panic (broken pipe)
- Upstream #913 — moss state info just says "no metadata found" and nothing else

## Open upstream issues

### moss (42)

- [#913](https://github.com/aerynOS/os-tools/issues/913) — moss state info just says "no metadata found" and nothing else
- [#901](https://github.com/aerynOS/os-tools/issues/901) — Running `moss ste | false` leads to a panic
- [#868](https://github.com/aerynOS/os-tools/issues/868) — Can `moss index` be optimized?
- [#866](https://github.com/aerynOS/os-tools/issues/866) — moss won't uninstall kernels if the EFI partition is full
- [#846](https://github.com/aerynOS/os-tools/issues/846) — does moss cache downloads?
- [#813](https://github.com/aerynOS/os-tools/issues/813) — moss: Add support for better pkgset definitions, including virtual pkgsets
- [#797](https://github.com/aerynOS/os-tools/issues/797) — Add a `moss index --prune` operation, which removes all but the newest .stone releases
- [#785](https://github.com/aerynOS/os-tools/issues/785) — Moss appears to ignore boulder recorded uids and gids for installed files
- [#780](https://github.com/aerynOS/os-tools/issues/780) — Moss state list shows command arguments
- [#729](https://github.com/aerynOS/os-tools/issues/729) — Refactor the `moss search --provides/-p` flag to be more generally useful
- [#697](https://github.com/aerynOS/os-tools/issues/697) — moss: Shows incomplete download in some circumstances but still appears to complete update successfully
- [#684](https://github.com/aerynOS/os-tools/issues/684) — moss: Add `cache seed` and `cache export` commands
- [#660](https://github.com/aerynOS/os-tools/issues/660) — moss sync --to should probably not require write access to the moss DB
- [#628](https://github.com/aerynOS/os-tools/issues/628) — moss: Add auto-prune feature to delete old states or enforce a retention limit
- [#615](https://github.com/aerynOS/os-tools/issues/615) — moss: use traditional way to confirm installation (on Enter)
- [#614](https://github.com/aerynOS/os-tools/issues/614) — moss: show overall download speed
- [#599](https://github.com/aerynOS/os-tools/issues/599) — moss: Show a reboot message when a reboot is necessary.
- [#576](https://github.com/aerynOS/os-tools/issues/576) — moss: Failed installation/blitting results in breaking stage activation
- [#543](https://github.com/aerynOS/os-tools/issues/543) — moss: Custom root directory (destdir) doesn't get propagated to blsforme
- [#542](https://github.com/aerynOS/os-tools/issues/542) — moss/db: Unpacked size (installed size) of packages is not recorded
- [#525](https://github.com/aerynOS/os-tools/issues/525) — moss remove error message when package isn't installed is weird
- [#492](https://github.com/aerynOS/os-tools/issues/492) — Moss state: Consider amending logic so first state is never removed on `moss state prune`
- [#488](https://github.com/aerynOS/os-tools/issues/488) — moss: Add `fetch`, `cache seed` and `cache export` commands
- [#403](https://github.com/aerynOS/os-tools/issues/403) — moss: Add a "file system transaction driver" abstraction API
- [#342](https://github.com/aerynOS/os-tools/issues/342) — moss: Make `moss state prune` show progress bar + recoverable/recovered disk space at start/end of run
- [#333](https://github.com/aerynOS/os-tools/issues/333) — moss info does not show source-release, build-release nor repository origin properties
- [#322](https://github.com/aerynOS/os-tools/issues/322) — moss/boulder: Add tests and fixtures
- [#318](https://github.com/aerynOS/os-tools/issues/318) — moss: Add the ability to deprecate and replace recipes/.stones
- [#312](https://github.com/aerynOS/os-tools/issues/312) — moss: Work on `moss state ` UX
- [#305](https://github.com/aerynOS/os-tools/issues/305) — moss does not work when run from chroot (via arch linux)
- [#301](https://github.com/aerynOS/os-tools/issues/301) — moss: Show size of every package and overall packages size
- [#234](https://github.com/aerynOS/os-tools/issues/234) — moss: Support passing `--format=json` or similar to `moss inspect`
- [#233](https://github.com/aerynOS/os-tools/issues/233) — moss + boulder: Streamline version info commands/options/flags
- [#227](https://github.com/aerynOS/os-tools/issues/227) — Notes for a `moss boot` command built on existing code
- [#206](https://github.com/aerynOS/os-tools/issues/206) — moss-format: Support Auxiliary Dependency annotations
- [#205](https://github.com/aerynOS/os-tools/issues/205) — moss: Enable cobble-plugin so operations work on .stones directly
- [#128](https://github.com/aerynOS/os-tools/issues/128) — moss: Add post-activation trigger for pruning files belonging to known inactive uids/gids?
- [#123](https://github.com/aerynOS/os-tools/issues/123) — moss: Include other information than just the package name in `moss search`
- [#75](https://github.com/aerynOS/os-tools/issues/75) — moss: Add arg for `--ignore-file-conflicts`
- [#43](https://github.com/aerynOS/os-tools/issues/43) — moss: Support "features" ala cargo
- [#34](https://github.com/aerynOS/os-tools/issues/34) — Implement `moss search (sr)`
- [#19](https://github.com/aerynOS/os-tools/issues/19) — `moss compose` for transmuting serpent root transactions into OCI compatible images (overlayfs?)

### boulder (39)

- [#916](https://github.com/aerynOS/os-tools/issues/916) — boulder: Change `strip` and `debug` to take a filelist dictionary mapping instead of being global boolean
- [#854](https://github.com/aerynOS/os-tools/issues/854) — Change REUSE tag for boulder recipe new from AerynOS to aerynOS
- [#828](https://github.com/aerynOS/os-tools/issues/828) — triggers: Add trigger flag/bool property to disable trigger during boulder buildroot preparation
- [#825](https://github.com/aerynOS/os-tools/issues/825) — Consolidate version_parse crate and boulder new functionality
- [#818](https://github.com/aerynOS/os-tools/issues/818) — Add `boulder recipe eval` 
- [#817](https://github.com/aerynOS/os-tools/issues/817) — boulder: Customize script interpreter and version
- [#732](https://github.com/aerynOS/os-tools/issues/732) — Can Boulder do staged builds?
- [#592](https://github.com/aerynOS/os-tools/issues/592) — boulder: Export a JSON schema for use with editors and schema validation tools
- [#591](https://github.com/aerynOS/os-tools/issues/591) — boulder: Add unit tests for the perl draft functionality
- [#577](https://github.com/aerynOS/os-tools/issues/577) — boulder: Consider a strategy for adding documentation to recipe options
- [#573](https://github.com/aerynOS/os-tools/issues/573) — boulder should check `rundeps` on build time
- [#571](https://github.com/aerynOS/os-tools/issues/571) — boulder: Localized man3 pages do not get patterned to -devel
- [#556](https://github.com/aerynOS/os-tools/issues/556) — boulder enhancement for packaging
- [#540](https://github.com/aerynOS/os-tools/issues/540) — boulder: Consider whether we can improve the output from various build systems
- [#534](https://github.com/aerynOS/os-tools/issues/534) — Also upload boulder in the release workflow
- [#499](https://github.com/aerynOS/os-tools/issues/499) — Write progress status conforming to OSC progress state escape sequence where appropriate in moss/boulder
- [#498](https://github.com/aerynOS/os-tools/issues/498) — boulder: fails to rebuild without root cache being removed
- [#486](https://github.com/aerynOS/os-tools/issues/486) — boulder: Add a marker in manifest.bin for what version of boulder it was built against
- [#476](https://github.com/aerynOS/os-tools/issues/476) — boulder: Add user-customisable buildroot package install set to improve packager UX
- [#474](https://github.com/aerynOS/os-tools/issues/474) — boulder: Update fortran flags for LLVM 20
- [#458](https://github.com/aerynOS/os-tools/issues/458) — boulder: transitive deps from macros should be recorded as builddeps in the manifest
- [#444](https://github.com/aerynOS/os-tools/issues/444) — Boulder doesn't use setup for selecting build dependencies 
- [#419](https://github.com/aerynOS/os-tools/issues/419) — boulder: Make non /usr/ build artefact warnings more visible and add more context
- [#408](https://github.com/aerynOS/os-tools/issues/408) — Boulder: install step fails to create required dirs
- [#406](https://github.com/aerynOS/os-tools/issues/406) — boulder: Improve splitting pattern testing story
- [#376](https://github.com/aerynOS/os-tools/issues/376) — boulder: Make boulder's own code (i.e. outside of external .yaml fields) self-documenting re. macros
- [#368](https://github.com/aerynOS/os-tools/issues/368) — boulder: Add build level lockfile functionality to avoid builds of the same recipe clobbering each other
- [#362](https://github.com/aerynOS/os-tools/issues/362) — boulder: Add optional `-fsplit-machine-functions` tuning flag for PGO optimize builds
- [#274](https://github.com/aerynOS/os-tools/issues/274) — boulder: Create a shared compiler cache directory for rootless executions
- [#264](https://github.com/aerynOS/os-tools/issues/264) — boulder: Consider adding a separate `fetch` phase
- [#250](https://github.com/aerynOS/os-tools/issues/250) — boulder/moss-format: Enable reading ELF_DLOPEN_METADATA notes
- [#232](https://github.com/aerynOS/os-tools/issues/232) — boulder: Exclude dependencies
- [#225](https://github.com/aerynOS/os-tools/issues/225) — boulder: Profile script keys should fall through to global keys if undefined in profile
- [#222](https://github.com/aerynOS/os-tools/issues/222) — boulder: Ensure i386/emul32 and x86_64 builds are built in isolated %(installroots)
- [#216](https://github.com/aerynOS/os-tools/issues/216) — boulder: Improve the workflow for updating recipes
- [#213](https://github.com/aerynOS/os-tools/issues/213) — boulder: binary manifests don't list the files a build will generate?
- [#204](https://github.com/aerynOS/os-tools/issues/204) — boulder: Add .stone size and throughput status in emit phase
- [#124](https://github.com/aerynOS/os-tools/issues/124) — boulder: Add the ability to `%export` files to a dedicated export dir accessible after the build
- [#86](https://github.com/aerynOS/os-tools/issues/86) — Mount user cache as overlay to system cache

### other (40)

- [#907](https://github.com/aerynOS/os-tools/issues/907) — state rollback from the boot menu dies in initramfs with “no ESP mounted in image mode”
- [#879](https://github.com/aerynOS/os-tools/issues/879) — Supplying urls with encoded URI components; ie: `%` inside them causes errors
- [#857](https://github.com/aerynOS/os-tools/issues/857) — Change how detached ("ephemeral") roots work
- [#823](https://github.com/aerynOS/os-tools/issues/823) — Asset paths use hashes with leading 0s removed
- [#811](https://github.com/aerynOS/os-tools/issues/811) — version_parse: fails to update on godot package
- [#799](https://github.com/aerynOS/os-tools/issues/799) — version_parse: fail to update python-numpy
- [#790](https://github.com/aerynOS/os-tools/issues/790) — KDL recipe format proposal
- [#783](https://github.com/aerynOS/os-tools/issues/783) — Docker support
- [#782](https://github.com/aerynOS/os-tools/issues/782) — `bsdtar-static: Error opening archive: Unrecognized archive format`
- [#763](https://github.com/aerynOS/os-tools/issues/763) — indicatif progress bar updates can overwrite output from tracing
- [#635](https://github.com/aerynOS/os-tools/issues/635) — Add x86_64-v4 support
- [#558](https://github.com/aerynOS/os-tools/issues/558) — Add sane, streamlined reporting capability via the `tracing` crate, w/ stdout = normal output and stderr = error output
- [#541](https://github.com/aerynOS/os-tools/issues/541) — stone: Installed size & download size are not recorded in application/x-stone-binary files
- [#533](https://github.com/aerynOS/os-tools/issues/533) — Change the release workflow to use our minimum supported Rust version
- [#524](https://github.com/aerynOS/os-tools/issues/524) — Removal of package after installation on un-synced system fails
- [#456](https://github.com/aerynOS/os-tools/issues/456) — URLs of files with special characters like + need to be HEX encoded before download  when s3 storage is used
- [#437](https://github.com/aerynOS/os-tools/issues/437) — Multiarch support 
- [#427](https://github.com/aerynOS/os-tools/issues/427) — consider allowing variables in the upstreams key to help scriptability
- [#424](https://github.com/aerynOS/os-tools/issues/424) — build deps parsing breaks: with only ghc_filesystem
- [#420](https://github.com/aerynOS/os-tools/issues/420) — Statelessness: Settle on a uapi / freedesktop "hermetic /usr" compatible statelessness story
- [#411](https://github.com/aerynOS/os-tools/issues/411) — Add version-gating for format interactions
- [#410](https://github.com/aerynOS/os-tools/issues/410) — Design rudimentary delta (V2)
- [#409](https://github.com/aerynOS/os-tools/issues/409) — Define V2 stone format
- [#397](https://github.com/aerynOS/os-tools/issues/397) — Request: provide a method for installing custom kernels
- [#394](https://github.com/aerynOS/os-tools/issues/394) — `xattr` support
- [#377](https://github.com/aerynOS/os-tools/issues/377) — Dynamically control the number of parallel downloads
- [#339](https://github.com/aerynOS/os-tools/issues/339) — format: Restore timestamps in layout::Entry
- [#288](https://github.com/aerynOS/os-tools/issues/288) — Record ghost paths for `kmod`
- [#287](https://github.com/aerynOS/os-tools/issues/287) — Add trigger caches
- [#285](https://github.com/aerynOS/os-tools/issues/285) — Conditionally execute boot management 
- [#259](https://github.com/aerynOS/os-tools/issues/259) — Distinguish between strong and weak dependencies + capture undeclared dlopen()s
- [#228](https://github.com/aerynOS/os-tools/issues/228) — libstone: Shared library for ecosystem integration
- [#199](https://github.com/aerynOS/os-tools/issues/199) — Improve the repository format
- [#197](https://github.com/aerynOS/os-tools/issues/197) — Minimise our required crate dependencies
- [#185](https://github.com/aerynOS/os-tools/issues/185) — Support translations across tooling projects
- [#155](https://github.com/aerynOS/os-tools/issues/155) — [UX] Show progress bars only when they are significant
- [#142](https://github.com/aerynOS/os-tools/issues/142) — Serpent OS migration tool that can discover uids/gids and installed packages
- [#114](https://github.com/aerynOS/os-tools/issues/114) — Multi-version Support?
- [#50](https://github.com/aerynOS/os-tools/issues/50) — Dual-signature system for .stone
- [#49](https://github.com/aerynOS/os-tools/issues/49) — Support BLAKE3

## Open upstream pull requests

PRs cannot be copied as PRs (they are branches in other forks). This list is for reference / cherry-pick evaluation only.

- [#915](https://github.com/aerynOS/os-tools/pull/915) — Miscellaneous Code Cleanups — @TheLostLambda
- [#914](https://github.com/aerynOS/os-tools/pull/914) — Brooks's CLI &lt;-&gt; lib split experiments (draft) — @TheLostLambda
- [#910](https://github.com/aerynOS/os-tools/pull/910) — moss: CLI &lt;-&gt; lib design proposal w/ code examples (draft) — @ermo
- [#898](https://github.com/aerynOS/os-tools/pull/898) — Implement expected cli output tests (draft) — @Microwonk
- [#873](https://github.com/aerynOS/os-tools/pull/873) — moss: Send FS_IOC_REVOKE_WATCHES ioctl post atomic-swap (draft) — @joebonrichie
- [#872](https://github.com/aerynOS/os-tools/pull/872) — boulder: Disable forced 128bit vector width by default (draft) — @joebonrichie
- [#869](https://github.com/aerynOS/os-tools/pull/869) — Cargo.toml: Drop unused dependencies — @livingsilver94
- [#862](https://github.com/aerynOS/os-tools/pull/862) — boulder/data: Add LLVM CREL tuning flags — @joebonrichie
- [#842](https://github.com/aerynOS/os-tools/pull/842) — crates/triggers: Support argument expansion with :all/:each (draft) — @joebonrichie
- [#836](https://github.com/aerynOS/os-tools/pull/836) — [WIP] Add fstree driver API & initial erofs driver (draft) — @tarkah
- [#833](https://github.com/aerynOS/os-tools/pull/833) — Format states as EROFS meta-only images — @tarkah
- [#815](https://github.com/aerynOS/os-tools/pull/815) — moss::cli: Add dynamic shell completions — @otherJL0
- [#788](https://github.com/aerynOS/os-tools/pull/788) — Consolidate `search-file` command into `search` (draft) — @otherJL0
- [#781](https://github.com/aerynOS/os-tools/pull/781) — boulder: Add convenient %install_licenses macro (draft) — @ermo
- [#750](https://github.com/aerynOS/os-tools/pull/750) — Add some error context to package analysis handlers (draft) — @jplatte
- [#733](https://github.com/aerynOS/os-tools/pull/733) — crates: Add fanotify (draft) — @joebonrichie
- [#718](https://github.com/aerynOS/os-tools/pull/718) — Update nix to v0.31.2 & associated API changes (draft) — @joebonrichie
- [#701](https://github.com/aerynOS/os-tools/pull/701) — Execute triggers in parallel batches (draft) — @joebonrichie
- [#676](https://github.com/aerynOS/os-tools/pull/676) — Add example of an output / emit API (draft) — @tarkah
- [#654](https://github.com/aerynOS/os-tools/pull/654) — Make vfs::tree::Kind pointer-sized (draft) — @jplatte
- [#650](https://github.com/aerynOS/os-tools/pull/650) — Some more involved string optimizations (draft) — @jplatte
- [#644](https://github.com/aerynOS/os-tools/pull/644) — Trigger caching (draft) — @tarkah
- [#570](https://github.com/aerynOS/os-tools/pull/570) — boulder: Add '--build', '--mv-to-repo=', and '--re-index' flags (draft) — @bhh32
- [#549](https://github.com/aerynOS/os-tools/pull/549) — Stone lockfiles (draft) — @barne856
- [#548](https://github.com/aerynOS/os-tools/pull/548) — WIP: Changes in moss required by packagekit backend (draft) — @joebonrichie
- [#536](https://github.com/aerynOS/os-tools/pull/536) — github/cargo: Some compilation changes — @ReillyBrogan
- [#423](https://github.com/aerynOS/os-tools/pull/423) — add safeguard to prevent moss from eating your current operating system (draft) — @cameronbraid
- [#340](https://github.com/aerynOS/os-tools/pull/340) — moss/boulder: Add perl providers (draft) — @joebonrichie
- [#316](https://github.com/aerynOS/os-tools/pull/316) — moss/boulder: Add support for font providers (draft) — @joebonrichie
- [#283](https://github.com/aerynOS/os-tools/pull/283) — boulder/moss: Reduce binary size by reducing dependency features (draft) — @ReillyBrogan
- [#241](https://github.com/aerynOS/os-tools/pull/241) — repo: Release improvements (draft) — @ReillyBrogan
- [#218](https://github.com/aerynOS/os-tools/pull/218) — Feat/cobble (draft) — @tarkah
- [#191](https://github.com/aerynOS/os-tools/pull/191) — Avoid regex in fnmatch crate — @livingsilver94
- [#170](https://github.com/aerynOS/os-tools/pull/170) — Example of eyre use for extract command (draft) — @tarkah
