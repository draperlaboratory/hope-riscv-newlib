@Library('hope-jenkins-library')_


def getGitBranchName() {
    return scm.branches[0].name
}

submitTopBuild([
    project: "newlib",
    branch: getGitBranchName()
])
