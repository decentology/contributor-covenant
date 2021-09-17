# Contributor Covenant

We at Decentology strongly believe in fostering individual creativity, and thus
we're very light on process. However, a small amount of process, if done right,
can greatly minimize friction when working with others.

This repository is your starting point to the awesome world of Decent
Repositories, let's GO!

## Branches

Before you can contribute, you need to make sure that you're doing so from the
right place. Even though we're not there yet, but ideally, each repository will
follow this specific pattern.

```
trunk [default]
⬇
staging
⬇
production
```

### `trunk`

These 3 branches form the core of each repository. `trunk` is where we all
should start, and it contains the bleeding edge commit. If you're working on a
new feature, or fixing a bug, you should always branch out from `trunk`.

Pick between `feature/` and `fix/` as the prefix, and then follow up with
brief space-separated title.

```sh
git checkout -b feature/adding-a-new-blockchain
git checkout -b fix/broken-links
```

After you complete your work, please create a **Pull request** and assign it to
someone that's an established contributor to that repository. They will make
sure to review your code and either merge it, or ask for further changes.

### `staging`

Periodically, `trunk` will be merged into `staging` for testing and making sure
the code is ready for production. This is the last stop before `production` and
it's critical that all bugs be squashed before code leaves `staging`.

### `production`

As per the name, this code is live and people depend on it to work. Only
repository authors and maintainers can merge into `production`.

## Pull Requests

We should never use `git merge` locally, and instead create **Pull requests**
whenever we want to merge our code back into `trunk`, or even a code review.

Once a pull request is merged, the branch is auto-removed from the repository.

To keep this document alive, I'm adding every potential contributor below with
the expectation that you will...

1. Clone this repository: `git clone`.
2. Create a feature branch: `git checkout -b feature/name`.
3. Update `readMe.md` with a ✅ next to your name.
4. Create a pull request and assign it to me, *decentMorgan*.

# Signatories

- ▢ Angelica Turla
- ▢ Jacob Tucker
- ✅ Jonathan Sheely
- ✅ Morgan Wilde
- ▢ Nik Kalyani
