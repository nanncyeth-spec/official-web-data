## HashKey Chain Mainnet Upgrade Announcement

## Overview

HashKey Chain will undergo a mainnet upgrade on Wednesday, April 16, 2025, to enhance network stability and fee control capabilities.

## Upgrade Details

I- Upgrade Type: Mainnet Upgrade
- Upgrade Topic: HashKey Chain Mainnet OP Version Upgrade
- Upgrade Content:
  - Upgrade Documentation: op-stack upgrade
  - Previous op-node 1.11.x version had a bug in blob fee calculation parameters, which may cause overcharging when L1 blob prices are high
  - Testnet Upgrade Test Report: https://tczezm50za.feishu.cn/docx/QA6OdGWXeo7C0QxUii3cUH8dnti
  - Bug Details: https://docs.optimism.io/notices/blob-fee-bug
  - OP officially recommends upgrading before the Pectra blob upgrade
  - Upgrade Version: op-node 1.12.2
  - Related Release Information: 
    - op-node v1.12.0 Release Notes 
    https://github.com/ethereum-optimism/optimism/releases/tag/op-node%2Fv1.12.0
    - op-node v1.12.1 Release Notes
    https://github.com/ethereum-optimism/optimism/releases/tag/op-node%2Fv1.12.1
    - op-node v1.12.2 Release Notes
    https://github.com/ethereum-optimism/optimism/releases/tag/op-node%2Fv1.12.2

## Impact

This is a seamless upgrade that should not affect on-chain operations under normal circumstances. However, developers are still advised to:
- Plan on-chain operations in advance
- Avoid executing critical interactions during the maintenance period
- Monitor the status of their applications

## Next Steps

After the upgrade is completed, blockchain operations will automatically return to normal. Users do not need to perform any additional actions.
If you have any questions or concerns, please contact the HashKey Chain support team.

— HashKey Chain Team
