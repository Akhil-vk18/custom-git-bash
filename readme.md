# Custom Git Bash Prompt Setup

This repository customizes your **Git Bash terminal** with:
- A pink startup banner (`.bashrc`)
- A custom prompt (`git-prompt.sh`) with:
  - current time
  - custom text (`Hey Machu`)
  - current folder
  - Git branch/status (via `__git_ps1`)
  - emoji prompt (`👽 >>`)

## Repository Files

- `/tmp/workspace/Akhil-vk18/custom-git-bash/.bashrc`  
  Adds terminal colors and a welcome banner.

- `/tmp/workspace/Akhil-vk18/custom-git-bash/git-prompt.sh`  
  Defines the Git Bash prompt style and Git completion integration.

## Install on Your System (Windows Git Bash)

> Run Git Bash as Administrator if required for writing inside `Program Files`.

1. **Backup your current files**
   - Backup `~/.bashrc`
   - Backup `C:\Program Files\Git\etc\profile.d\git-prompt.sh`

2. **Copy `.bashrc` to your Git Bash home directory**
   - Destination in Git Bash: `~/.bashrc`

3. **Copy `git-prompt.sh` to Git for Windows profile scripts**
   - Destination: `C:\Program Files\Git\etc\profile.d\git-prompt.sh`

4. **Restart Git Bash**
   - Close all Git Bash windows and open a new one.

## Verify It Works

After restart, you should see:
- A pink “Git Bash Ready! 🚀” banner
- Prompt containing time + custom text + folder + Git branch
- Final input line starting with `👽 >>`

## Notes

- If you do not see Git branch info, ensure `git-completion.bash` and `git-prompt.sh` exist in your Git installation.
- You can edit color/text values in `.bashrc` and `git-prompt.sh` to personalize further.
