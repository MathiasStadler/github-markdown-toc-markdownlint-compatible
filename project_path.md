# project path
<!-- keep the format -->
https://stackoverflow.com/questions/16826657/how-to-exit-a-shell-script-if-targeted-file-doesnt-exist
Add extension TODO Highlight
<!-- keep the format -->
## init plain project structure
<!-- keep the format -->
```bash <!-- markdownlint-disable-line code-block-style -->
create_folder_file=".vscode" && if [[ (-f ${create_folder_file} ) || ( -d ${create_folder_file} ) || (-L ${create_folder_file}) ]]; \
then echo "folder/file/link ${create_folder_file} exists"; \
else echo "folder/file/link ${create_folder_file} NOT exists";\
fi \
mkdir -p .vscode \
&& touch .vscode/settings.json \
&& cat <<EoF >.vscode/settings.json
{
    "cSpell.words": [
        "binutils",
        "ccache",
        "debian",
        "jupyter",
        "debuginfo",
        "euxo",
        "evcxr",
        "FIXIT",
        "grcov",
        "nextest",
        "objcopy",
        "objdump",
        "pipefail",
        "profdata",
        "readobj",
        "rustfilt",
        "rustup",
        "sccache"
    ],
    "todo-tree.regex.regex": "(//|#|<!--|;|/\\\\*|^|^\\\\s*(-|\\\\d+.))\\\\s*($TAGS)",
    "todo-tree.general.tags": [
        "BUG",
        "HACK",
        "FIXME",
        "TODO",
        "XXX",
        "[ ]",
        "[x]"
    ]
}
EoF


###
create_folder_file=".vscode" && if [[ -f $create_folder_file ]] ; then echo "folder/file ${create_folder_file} exists";else echo "folder/file ${create_folder_file} NOT exists"; fi

if [[ -L "$file" && -d "$file" ]]

create_folder_file=".vscode" && if [[ -d ${create_folder_file} && -L ${create_folder_file} && -f ${create_folder_file} ]]; \
then echo "folder/file/link ${create_folder_file} exists"; \
else echo "folder/file/link ${create_folder_file} NOT exists"; fi
###
create_folder_file=".vscode" && if [[ (-f ${create_folder_file} ) || ( -L ${create_folder_file} ) ]]; \
then echo "folder/file/link ${create_folder_file} exists"; \
else echo "folder/file/link ${create_folder_file} NOT exists"; fi

###
create_folder_file=".vscode" && if [[ (-f ${create_folder_file} ) || ( -d ${create_folder_file} ) || (-L ${create_folder_file}) ]]; then echo "folder/file/link 
${create_folder_file} exists"; else echo "folder/file/link ${create_folder_file} NOT exists"; fi

###
create_folder_file=".vscode" && if [[ (-f ${create_folder_file} ) || ( -d ${create_folder_file} ) || (-L ${create_folder_file}) ]]; \
then echo "folder/file/link ${create_folder_file} exists"; \
else echo "folder/file/link ${create_folder_file} NOT exists";\
fi

- utility's
  - Link sign
