# Test_Ground

# C++ Practice Programs

### Solar System Exploration, 1950s – 1960s

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

file_count()
{
    if [ ! -e "$1" ]
    then
        exit 1
    fi

    local -i files=$(find "$(readlink -f -- "$1")" -type f -print0 | grep -cz -- -)
    echo $files
}