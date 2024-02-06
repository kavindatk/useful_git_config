# useful_git_config
GitHub problems and hotfixes


**Disable SSL Verification**

The quickest and easiest way is to globally disable SSL verification on Git to clone the repository. But after cloning, you will immediately enable it again, otherwise Git won't verify certificate signatures for other repositories.

    1. Disable SSL verification on Git globally:

    git config --global http.sslVerify false

    2. Clone your repository:

    git clone <your repo>

    3. Enable SSL verification on Git globally:

    git config --global http.sslVerify true

    4. Change directory into your repo:

    cd <your repo>

    5. Disable SSL verification only on your repository:

    git config --local http.sslVerify false

Happy Coding....!