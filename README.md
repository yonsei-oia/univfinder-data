# univfinder-data

Public exchange university data for student dashboard. Mirrored from yonsei-oia/univfinder-backoffice.

> **This repository is not open source.** The files here are published only so
> that the official Yonsei OIA UnivFinder dashboard can load them at runtime.
> No license to copy, redistribute, or reuse the data is granted.
>
> Reproduction or redistribution of a substantial part of this database,
> automated collection, and use for AI training or fine-tuning are prohibited
> without prior written permission. See [`LICENSE`](LICENSE).
>
> 본 저장소는 오픈소스가 아닙니다. 파견교 데이터는 연세대학교 국제처가 관리하며,
> 사전 허가 없는 복제·재배포·자동 수집 및 AI 학습 목적의 이용을 금지합니다.

- Terms of use: <https://oia.yonsei.ac.kr/univfinder> → 이용안내 / Terms of Use
- Contact: abroad@yonsei.ac.kr

## Attribution

Citation or secondary use requires prior enquiry and the following attribution:

```
데이터 출처: 연세대학교 국제처 OIA UnivFinder (https://oia.yonsei.ac.kr/univfinder)
```

## Accuracy

Partner university information (quotas, eligibility and language requirements,
deadlines) changes each semester. These files are provided for the operation of
the official dashboard and carry no warranty of accuracy or currency. Final
verification must be based on official OIA announcements and on information
published by the host institution.

## Contents

| File | Description |
|---|---|
| `universities-data.json` | Partner universities, regular semester exchange |
| `universities-updates.json` | Change history feed for the regular finder |
| `seasonal-data.json` | Summer / Winter seasonal programs |
| `seasonal-updates.json` | Change history feed for the seasonal finder |
| `universities-notes.json` | Legacy notes (retired; retained for reference) |

Files are mirrored automatically by the `sync` and `sync-seasonal` workflows in
the private backoffice repository. Do not edit them here — changes are
overwritten on the next mirror run.
