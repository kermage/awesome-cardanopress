# Awesome CardanoPress

> *A curated list of **CardanoPress** awesomeness*

## Official Resources

- [Website](https://cardanopress.io)
- [Repository](https://github.com/cardanopress)
- [Discord](https://discord.com/invite/CEX4aSfkXF)
- [Twitter](https://twitter.com/cardanopress)

## Available Hooks

### Actions

- [cardanopress_loaded](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Installer.php#L39)
- [cardanopress_wallet_status_checks](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L98)
- [cardanopress_associated_assets](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L126)
- [cardanopress_associated_asset](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L135)
- [cardanopress_account_history](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L182)
- [cardanopress_blockfrost_init](https://github.com/CardanoPress/cardanopress/blob/d65fb6137fd5ccae8753b29284e2ce2d6b735ae1/src/Blockfrost.php#L23)

### Filters

- [cardanopress_ajax_messages](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L70)
- [cardanopress_error_messages](https://github.com/CardanoPress/cardanopress/blob/d65fb6137fd5ccae8753b29284e2ce2d6b735ae1/src/Actions/CoreAction.php#L86)
- [cardanopress_script_messages](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Actions/CoreAction.php#L77)
- [cardanopress_sanitization_messages](https://github.com/CardanoPress/cardanopress/blob/a288551e823cf8c72399c1ca6353b78e433f1719/src/Actions/Sanitization.php#L31)
- [cardanopress_sanitization_$field_key](https://github.com/CardanoPress/cardanopress/blob/d65fb6137fd5ccae8753b29284e2ce2d6b735ae1/src/Actions/Sanitization.php#L45)

## Available Shortcodes

- [cardanopress_option](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L33-L47)
- [cardanopress_template](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L49-L75)
- [cardanopress_template_if](https://github.com/CardanoPress/cardanopress/blob/d65fb6137fd5ccae8753b29284e2ce2d6b735ae1/src/Shortcode.php#L78-L91)
- [cardanopress_userprofile](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L136-L151)
- [cardanopress_delegationpool](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L153-L167)
- [cardanopress_component_cardanopress](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L77-L91)
- [cardanopress_component_pooldelegation](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L93-L102)
- [cardanopress_component_paymentform](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L104-L121)
- [cardanopress_component_splitform](https://github.com/CardanoPress/cardanopress/blob/c17700e427da65efb19673e464a14040006d449a/src/Shortcode.php#L123-L134)

## Customization Examples

- [Additional dropdown menu items inserted before "Disconnect"](https://gist.github.com/kermage/796f154de0f18dd09f8e3df12e112fb9)
- ["Tipping user" or sending custom payments to a specified address](https://gist.github.com/kermage/e3fd34801a0a06917d2fa5c36516bed3)
  - [Simplified version with one button tag and one attribute](https://gist.github.com/kermage/bc9ccf85f53d8eb503660d48c3bee6a1)
- [Skip listing the ADA Handles in the collection page](https://gist.github.com/kermage/0df6c9c4ec87b539d6c5b924c5925587)
- [Only show specific wallet/s in the modal connect](https://gist.github.com/kermage/22b0cb6206c703d7b2f3eebd66a9174f)

## Extras

- [Allow to easily update to latest GitHub version releases](https://github.com/kermage/cardanopress-edge-user)
