Commands
jekyll serve
npm install grunt --save-dev
`for file in ./*; do cwebp -q 50 "$file" -o "${file%.*}.webp"; done`