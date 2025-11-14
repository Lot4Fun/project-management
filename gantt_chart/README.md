# Gantt Chart Template

## タグについて

Mermaidのガントチャートで使用するタグは以下の通り。

| ステータス | 本書での使い方 | 参考：一般的な使い方 |
| --- | --- | --- |
| crit   | 計画 | クリティカルなタスク |
| active | 実績 | 進行中のタスク |
| done   | 完了 | 完了したタスク |

これらは組み合わせて使うことも可能。

| 組み合わせ | 説明 |
| --- | --- |
| crit,active | クリティカルで進行中 |
| crit,done | クリティカルで完了済み |

## テーマ設定テンプレート

```text
%%{
    init: {
        'theme': 'default',
        'themeVariables': {
            'sectionBkgColor': '#d1d1ff',
            'altSectionBkgColor': '#d1d1ff',
            'sectionBkgColor2': '#d1d1ff',

            'textColor': '#000000',
            'taskTextLightColor': '#000000',
            'taskTextDarkColor': '#000000',

            'taskBkgColor': 'transparent',
            'taskBorderColor': 'transparent',

            'taskTextColor': '#000000',
            'taskTextOutsideColor': '#000000',
            'critBkgColor': '#b7c7f8',
            'critBorderColor': '#b7c7f8',

            'activeTaskBkgColor': '#ffa965',
            'activeTaskBorderColor': '#ffa965',

            'doneTaskBkgColor': '#c0c0c0',
            'doneTaskBorderColor': '#c0c0c0'
        }
    }
}%%
```
