# dreamlabs-skills
Dreamlabs Skills

# Skills 扫描过程

## 全局扫描
* ~/.agents/skills目为双方共享的Skills目录
* ~/.agents/skills

## 应用扫描
### OpenClaw扫描
* ~/.openclaw/skills
### Hermes扫描
* ~/.hermes/skills

## Agent扫描
### OpenClaw扫描
* ~/.openclaw/${workspace}/skills
### Hermes扫描
* 待定

## 第三方目录扫描
### OpenClaw扫描
例如：把 ~/Work/Frameworks/Github/dreamlabs-skills/my-skills 链接到 OpenClaw 全局 skills
ln -s ~/Work/Frameworks/Github/dreamlabs-skills/my-skills ~/.openclaw/skills/my-skills
### Hermes扫描
例如：把 ~/Work/Frameworks/Github/dreamlabs-skills/my-skills 链接到 Hermes 全局 skills
ln -s ~/Work/Frameworks/Github/dreamlabs-skills/my-skills ~/.hermes/skills
