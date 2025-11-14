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
            'sectionBkgColor': '#b3b3ff',
            'altSectionBkgColor': '#b3b3ff',
            'sectionBkgColor2': '#b3b3ff',

            'textColor': '#ffffff',
            'taskTextLightColor': '#000000',
            'taskTextDarkColor': '#ffffff',

            'taskBkgColor': 'transparent',
            'taskBorderColor': 'transparent',
            'taskTextColor': '#ffffff',

            'critBkgColor': '#000080',
            'critBorderColor': '#000080',
            'critTextColor': '#ffffff',

            'activeTaskBkgColor': '#ff4500',
            'activeTaskBorderColor': '#ff4500',

            'doneTaskBkgColor': '#808080',
            'doneTaskBorderColor': '#808080',

            'milestoneTextColor': '#ffffff'
        }
    }
}%%
```
