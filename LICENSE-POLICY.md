# Standing License Policy - Public Data Packages

Every public-launch data package must carry exactly one recorded license before
it ships.

1. **Source.** A package reuses the license of its direct data sources, or of
   the models used to synthesize its natural-language responses.
2. **Choice.** When a package has more than one such source, adopt the source
   whose terms are most permissive for derivative and secondary use - that is,
   commercial reuse, redistribution and modification of derived data.
3. **Evidence.** Read the license from the source itself. Catalogue tags and
   short license names are not sufficient evidence; custom licenses must be
   read in full.
4. **Recording.** Record the license exactly as declared by the chosen source
   (its SPDX identifier or declared license string) together with the
   repository identifier of that source.
5. **Blocking.** If no source grants usable rights for the package's data,
   record the package as `BLOCKED` and do not publish it.
