{
  "coding_instruct": {
    "file_name": "coding_instruct/train.json",
    "formatting": "alpaca",
    "columns": {
      "system": "system",
      "prompt": "instruction",
      "query": "input",
      "response": "output"
    },
    "tags": {
      "role_tag": null,
      "content_tag": null
    }
  },
  "coding_instruct_eval": {
    "file_name": "coding_instruct/eval.json",
    "formatting": "alpaca",
    "columns": {
      "system": "system",
      "prompt": "instruction",
      "query": "input",
      "response": "output"
    }
  },
  "coding_conversations": {
    "file_name": "coding_conversations/train.json",
    "formatting": "sharegpt",
    "columns": {
      "messages": "conversations",
      "system": "system"
    },
    "tags": {
      "role_tag": "from",
      "content_tag": "value",
      "user_tag": "human",
      "assistant_tag": "gpt"
    }
  },
  "coding_conversations_eval": {
    "file_name": "coding_conversations/eval.json",
    "formatting": "sharegpt",
    "columns": {
      "messages": "conversations",
      "system": "system"
    },
    "tags": {
      "role_tag": "from",
      "content_tag": "value",
      "user_tag": "human",
      "assistant_tag": "gpt"
    }
  }
}
