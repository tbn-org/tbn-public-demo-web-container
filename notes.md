https://towardsdatascience.com/kubernetes-application-deployment-with-aws-eks-and-ecr-4600e11b2d3c


https://www.passwordstore.org/
https://dev.to/glsolaria/storing-dockerhub-credentials-using-pass-on-ubuntu-18-04-2k9o
https://github.com/docker/docker-credential-helpers

https://qtpass.org/
sudo apt install qtpass
ls ~/.password-store/

pass init <gpg-id>
pass git init
pass git remote add origin https://github.com/username/repo.git
pass git push -u --all
pass git push
pass git pull

https://www.freecodecamp.org/news/how-to-fix-git-always-asking-for-user-credentials/

git remote set-url origin git@github.com:username/repo.git
git config --global credential.helper store
git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=600'

https://devhints.io/pass
https://medium.com/@chasinglogic/the-definitive-guide-to-password-store-c337a8f023a1
https://gist.github.com/abtrout/d64fb11ad6f9f49fa325
https://git.zx2c4.com/password-store/about/
https://www.gnupg.org/%28es%29/related_software/gpgme/index.html




sudo apt install golang-github-proglottis-gpgme-dev
go get github.com/cortex/gopass
go get github.com/proglottis/gpgme

npm start

https://www.digitalocean.com/community/tutorials/how-to-set-up-a-private-docker-registry-on-ubuntu-18-04
https://nodejs.dev/learn/output-to-the-command-line-using-nodejs
