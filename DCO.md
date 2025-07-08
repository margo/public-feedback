# Developer Certificate of Origin (DCO)

This App enforces the [Developer Certificate of Origin (DCO)](https://developercertificate.org/) on Pull Requests. It requires all commit messages to contain the Signed-off-by line with an email address that matches the commit author.

The Developer Certificate of Origin (DCO) is a lightweight way for contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project. [Here is the full text](https://developercertificate.org/) of the DCO, reformatted for readability:


> By making a contribution to this project, I certify that:
>
> 1. The contribution was created in whole or in part by me and I have the right to submit it under the open >source license indicated in the file; or
>
> 2. The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or
> 3. The contribution was provided directly to me by some other person who certified 1., 2. or 3. and I have not modified it.
> 4. I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.


Contributors sign-off that they adhere to these requirements by adding a Signed-off-by line to commit messages.

> This is my commit message
> Signed-off-by: Random J Developer <random@developer.example.org>

Git even has a -s command line option to append this automatically to your commit message:

> $ git commit -s -m 'This is my commit message'

Once installed, this integration will set the status to failed if commits in a Pull Request do not contain a valid Signed-off-by line.

![image](https://github.com/user-attachments/assets/dffa4366-9be4-40f9-8260-7e847719c8e0)

The [Margo Charter](https://github.com/margo/Margo-collaboration/blob/main/non-executable-margo-membership-agremeent.pdf) onlining contribution requirements

