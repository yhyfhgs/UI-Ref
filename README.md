# UI Ref

Private collection of UI component reference repositories.

## References

| Reference | Local path | Upstream | License |
| --- | --- | --- | --- |
| shadcn/ui | [`references/shadcn-ui`](references/shadcn-ui) | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | [MIT](references/shadcn-ui/LICENSE.md) |

References are Git submodules. The parent repository records an exact upstream commit; the local checkout contains the reference source. The initial download uses shallow history.

### shadcn/ui entry points

- [Base UI components](references/shadcn-ui/apps/v4/registry/bases/base/ui)
- [Radix components](references/shadcn-ui/apps/v4/registry/bases/radix/ui)
- [Component examples](references/shadcn-ui/apps/v4/examples)
- [Documentation source](references/shadcn-ui/apps/v4/content/docs)

## Clone with reference sources

```sh
git clone --recurse-submodules --shallow-submodules https://github.com/yhyfhgs/UI-Ref.git
```

If the parent repository has already been cloned:

```sh
git submodule update --init --recursive --depth 1
```

Check pinned reference revisions:

```sh
git submodule status
```

## Adding references

```sh
git submodule add --depth 1 https://github.com/OWNER/REPOSITORY.git references/NAME
```

Add an entry to the table above, then commit `.gitmodules`, the new submodule, and the README together. Preserve each upstream project's license and attribution.
