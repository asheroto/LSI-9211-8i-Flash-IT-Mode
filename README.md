# Files to Flash LSI 9211-8i using EFI shell

See this article: https://www.truenas.com/community/threads/how-to-flash-lsi-9211-8i-using-efi-shell.50902/

Some links in the article are broken, so this repo includes the same files in the proper order. Format a flash drive as FAT32 and copy the files to its root for use. A file hash is provided below for verification.

You can download either the full repo or the release file. The release version excludes extras like README.md.

The EFI and BOOT folders contain identical files but were included—per the article—to help certain EFI systems detect the boot files properly.

| Filename      | SHA256 Hash                                                      |
| ------------- | ---------------------------------------------------------------- |
| 2118it.bin    | 9C35132531E515B3AA066BA2940F4C11BC953EB16EBA61D7A34620EB290D1CD2 |
| mptsas2.rom   | 745EA38FCABD8F233DD2233756501CAE5E662845CFD352C3B52BAF7AAD0672DF |
| README.md     | 59040357DB0FE0A4ED7B315D794BBAB06F34B74E639C4FE30B0E3AAC074138E0 |
| sas2flash.efi | B49C96AAD59BB9D126D06CE65EA38996644AAE7965EF744AA7BB89A9B4DCE7A1 |
| ShellX64.efi  | EA5E763A8A5F9733DBF7C33FFA16A19E078C6AF635B51D8457BC377A22106A8C |