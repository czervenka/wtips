# WTips
Winding Tree Improvement Proposals.

Our proposal process and documentation is a variant of [Ethereum EIPs](https://github.com/ethereum/EIPs)  with minimal modifications so anyone familiar with it will be familiar with our WTip as well.

Thanks to Ethereum team for all the work on setting efficient process.

# Contributing

 1. Fork the repository by clicking "Fork" in the top right.
 2. Add your WTip to your fork of the repository. There is a [template WTip here](wtip-X.md).
 3. Submit a Pull Request to Winding Tree's [WTip repository](https://github.com/windingtree/wtips).

Your first PR should be a first draft of the final WTip. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new WTip and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the WTip as a whole.

If your WTip requires images, the image files should be included in a subdirectory of the `assets` folder for that WTip as follow: `assets/wtip-X` (for wtip **X**). When linking to an image in the WTip, use relative links such as `../assets/wtip-X/image.png`.

When you believe your WTip is mature and ready to progress past the draft phase, you should open a PR changing the state of your WTip to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the WTip - they may close the PR and request that you fix the issues in the draft before trying again.

# WTip Status Terms
* **Draft** - an EIP that is undergoing rapid iteration and changes
* **Last Call** - an WTip that is done with its initial iteration and ready for review by a wide audience
* **Accepted** - a core WTip that has been in Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author
* **Deferred** - an WTip that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.
