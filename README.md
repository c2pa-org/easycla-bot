# C2PA and EasyCLA

The C2PA Steering Committee has adopted IPR policies for [Individual](PREVIEW-C2PA_Non-Member_Agreement-Individual-Contributors.pdf) and [Corporate](./PREVIEW-C2PA-Corporate-Contributor-Agreement.pdf) contributors to C2PA working groups, repositories and work documents. These documents are referred to below as the CLAs.

The C2PA uses [EasyCLA](https://lfcla.com) to ensure that all contributors have signed the appropriate documents when contributing to this project. This tool was created and is maintained by the Linux Foundation, and has a number of features designed to support our project communities:

* Once a contributor is authorized for one C2PA repo, the signature is recognized for any other C2PA repos that use EasyCLA.
* Contributors may sign as individuals, or their company can sign on their behalf.
* Companies who sign the CLA can authorize employee usernames individually, add an entire email domain, or specify a GitHub organization containing their employees as members.

There is no cost to sign the C2PA CLA. Please note that this is different from [membership in the C2PA](https://c2pa.org/membership/). If your organization relies upon our projects, [please become a member](https://c2pa.org/membership/). Membership dues are an essential source of funding and investment for this work.

## How to use EasyCLA

### Who signs the documents?

You can sign the C2PA CLA as an individual, or your company can sign and authorize you as a contributor. 

The individual workflow is for people who can make CLA commitments on their own behalf (e.g., hobbyists, students, sole proprietors, etc). This workflow is fast and easy, but may not be appropriate for people who are doing work-for-hire. The corporate workflow involves more steps, but allows a company to sign one document one time for all of their contributors.

At a high level, the signature process works like this:

1. Open a PR against a repo covered by EasyCLA (including this one).
1. A bot will check whether your GitHub user is covered by a signed CLA.
1. If you're already covered you will get a green checkmark, and your contribution can be merged.
1. If you're not covered, you'll be prompted through the signature process.

### Initiating the signature process against a test repo

The easiest way to initiate the process is to open a PR against any C2PA repo, including this one.

If you simply want to sign the documents in preparation for future contributions, you can open a trivial PR against this file (for example, to fix this spleling error) and you will be prompted through the process. PRs against this repo will be closed periodically.

## Sign as an individual

If you are working on your own behalf and can make IP commitments about what you produce, you can sign as an individual contributor using our Non-Member Agreement. ([Preview the document](./PREVIEW-C2PA_Non-Member_Agreement-Individual-Contributors.pdf))

1. Open a PR against a repo that uses EasyCLA.
1. When blocked by the bot, follow the prompts and choose *Individual*.
1. Fill in the details and sign the DocuSign form.
1. Wait a little while for the check to re-run.

That's all there is to it.

## Have your company sign for you

If you are doing work for someone else (e.g., it's your job), the company might need to sign for you. Companies can authorize multiple employees with a single signature. If your company has already signed the document but you're still blocked, you will need to request your username be added to the list of authorized contributors for your employer. Once this is complete you'll just have to confirm you work for them by clicking through the process one final time.

Here are the steps to have your company sign the CLA, captured in the Contributor Membership Agreement. ([Preview the document](./PREVIEW-C2PA-Corporate-Contributor-Agreement.pdf))

### If your company hasn't yet signed the agreement

1. Open a PR against a repo that uses EasyCLA.
1. When blocked by the bot, follow the prompts and choose *Corporate*.
1. Choose your company from the list. If it's not there, add it.
1. Designate someone with signing authority (generally an officer or attorney, if in doubt ask your manager) to receive the DocuSign. This person is the *CLA Manager*.
1. Follow up with the CLA Manager and ask them to sign the DocuSign form.
1. The CLA Manager can now designate other CLA Managers who are allowed to manage your company's list of authorized contributors.

### When your company has finished signing the agreement

1. Once the agreement is signed, any CLA manager can [log into the EasyCLA site](https://easycla.lfx.linuxfoundation.org/#/) (choose EasyCLA v2) and either:
  * Add your GitHub username individually to the list of authorized contributors, or
  * Add your corporate email domain, which authorizes anyone who has that email in their GitHub account, or
  * Add a corporate GitHub Organization, where any member of the org is covered by the CLA.
1. Once this is done, you'll need to click the *Details* link in the PR (again) and click a button that acknowledges you want to be covered by the company.
1. Wait a little while for the check to re-run.

At this point, your PRs will no longer be blocked by EasyCLA on any C2PA repo.

### Best practices

* Ask the CLA Manager to add the corporate email domain to the list of authorized contributors, or ask them to add your corporate GitHub organization. This is much easier than adding contributors individually.

## Getting help

If your company is in the system but you don't know who your CLA manager is, you can email [jburson@linuxfoundation.org](mailto:jburson@linuxfoundation.org).

If you run into issues, you can [open a ticket in JIRA](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143).
