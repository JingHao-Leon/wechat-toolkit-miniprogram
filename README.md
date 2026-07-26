# wechat-toolkit-miniprogram

A collection of WeChat mini-program pages and components built around a
**chatbot + agent UI** core. The toolkit includes:

- **voice check-in page** (`pages/voice-checkin`) — record a short audio clip,
  transcribe via ASR, post a structured check-in event to the host backend
- **chatBot page** (`pages/chatBot`) — streaming conversation UI with
  tool-call visualization
- **food list, business list, weather, map** widgets for the agent toolkit
- **agent-ui components** (`components/agent-ui`) — markdown, code block,
  file attachment, tool card, custom card, collapse and feedback atoms
  designed to be dropped into any mini-program

## Tech

- Native WeChat mini-program runtime (WXML / WXSS / JS), no compile-time
  framework
- Components use the agent-ui design language defined in
  `components/agent-ui/`

## Layout

```
miniprogram/
├── pages/
│   ├── index/            # home / launcher
│   ├── voice-checkin/    # record → ASR → structured event
│   ├── chatBot/          # streaming chat UI
│   └── foodBuy/          # demo page wiring food list + map
└── components/
    ├── agent-ui/         # chat file, markdown, tool card, ...
    └── toolCard/         # business-list, food-list, map, weather
```

## Project Status

This is the front-end layer; the agent backend is the
`blue-whale-voice-agent` / `ai-multimodal-platform` projects in the same
GitHub org. The mini-program is meant to be a drop-in client.

## Contact

GitHub: [JingHao-Leon](https://github.com/JingHao-Leon)  
Email:  262\*\*\*\*56@qq.com  
Phone:  159\*\*\*\*0000
