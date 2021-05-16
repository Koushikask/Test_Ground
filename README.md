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

![Hits](https://hitcounter.pythonanywhere.com/count/tag.svg?url=git%40github.com%3AKoushikask%2FTest_Ground)

#!/bin/bash
# count inodes for each directory
LIST=`ls`
for i in $LIST; do
echo $i
find $i -printf "%i\n" | sort -u | wc -l
done