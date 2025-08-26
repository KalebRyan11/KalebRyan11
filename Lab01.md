## Lab 01

- Name:
- Email:

## Part 1 - GitHub Profile

1. [your_github_username_here's GitHub Profile](FIXTHISURL-https://github.com/your_username)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | Displays help about Windows PowerShell cmdlets and concepts.       |
| Get-Location | pwd    | Displays the file path for where you currently are       |
| Get-ChildItem | ls    | Displaysall of the files or instances inside or a part of the current location your at       |
| mkdir   | mkdir       | make directory at current place       |
| Set-Location | cd     | jumps to loaction provided inside of current loaction      |
| New-Item | touch      | creates a new empty file at current loaction       |
| Move-Item | mv        |  moves specified item or file to new loaction      |
| Copy-Item | cp        |  copies the provied item      |
| Remove-Item | rm      |  deletes specified item      |
| notepad.exe | vim     |  opens the notepad application     |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: 

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:/Users/kaleb/
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: Set-Location DirA
5. Go into `Dir B` from `DirA`: cd "C:/Users/kaleb/Dir B"
6. Return to your user's home directory: cd "C:\Users\kaleb"
7. Create a file named `test.txt`: New-Item test.txt
8. Move the file named `test.txt` into `DirA`: Move-Item test.txt DirA
9. Contents of `test.txt`: Get-Content test.txt
```
Put your words here
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item test.txt copy.txt
11. View the contents of `DirA`: Get-ChildItem
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: "C:\Users\kaleb\DirA\test.txt" fodder.txt
13. Delete / remove both `fodder.txt` AND `Dir B`:  remove-Item "Dir B" then type Y

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



