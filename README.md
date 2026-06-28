# Tejas-Patil
https://tejasportfolio23.lovable.app
mkdir -p ~/tejas-portfolio-mirror
cd ~/tejas-portfolio-mirror

wget --mirror \
  --convert-links \
  --adjust-extension \
  --page-requisites \
  --no-parent \
  --span-hosts \
  --wait=1 \
  --limit-rate=200k \
  https://tejasportfolio23.lovable.app
