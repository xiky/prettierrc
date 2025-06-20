# prettierrc
{
  "$schema": "https://json.schemastore.org/prettierrc",
  "arrowParens": "always", // 箭头函数参数括号: "always" - 总是包含括号 (示例: `(x) => x`), "avoid" - 尽可能省略括号 (示例: `x => x`)
  "bracketSameLine": false, // 将HTML/JSX标签的 `>` 放在最后一行而非新行
  "bracketSpacing": true, // 在对象括号之间添加空格 (示例: `{ foo: bar }`)
  "cursorOffset": -1, // 调试用：输出格式化后光标位置
  "embeddedLanguageFormatting": "auto", // 处理嵌入代码: "auto" - 自动识别并格式化, "off" - 不格式化嵌入代码
  "endOfLine": "lf", // 换行符格式: "lf" - Linux/macOS风格 (\\n), "crlf" - Windows风格 (\\r\\n), "cr" - 旧版macOS风格 (\\r), "auto" - 保持原有风格
  "experimentalOperatorPosition": "end", // 操作符换行位置: "start" - 新行开头, "end" - 上一行结尾
  "experimentalTernaries": false, // 使用特殊三元组格式 (条件在前)
  "filepath": "", // 指定文件路径用于解析器推断
  "htmlWhitespaceSensitivity": "css", // HTML空白处理: "css" - 遵循CSS规则, "strict" - 严格保留, "ignore" - 忽略空白
  "insertPragma": false, // 自动在文件头部添加 `@format` 标记
  "jsxSingleQuote": false, // JSX中使用单引号替代双引号
  "objectWrap": "preserve", // 对象换行处理: "preserve" - 保持多行格式, "collapse" - 尽可能单行
  "parser": "babel", // 指定解析器 (如 "typescript", "scss", "json", "markdown", "html" 等)
  "plugins": [], // 添加插件数组 (如 ["prettier-plugin-tailwindcss"])
  "printWidth": 80, // 代码行最大宽度 (超出自动换行)
  "proseWrap": "preserve", // 文字段落换行: "always" - 超宽换行, "never" - 不换行, "preserve" - 保持原样
  "quoteProps": "as-needed", // 对象属性引号: "as-needed" - 必要时加引号, "consistent" - 需引号时全加, "preserve" - 保持原样
  "rangeEnd": null, // 仅格式化到指定字符位置 (exclusive)
  "rangeStart": 0, // 从指定字符位置开始格式化
  "requirePragma": false, // 仅格式化含 `@prettier` 或 `@format` 标记的文件
  "semi": true, // 语句末尾添加分号
  "singleAttributePerLine": false, // HTML/JSX/Vue中每行强制单个属性
  "singleQuote": false, // 使用单引号替代双引号
  "tabWidth": 2, // 每级缩进空格数
  "trailingComma": "all", // 多行尾部逗号: "all" - 所有可能位置 (含函数参数), "es5" - ES5兼容位置 (对象/数组), "none" - 无尾逗号
  "useTabs": false, // 使用制表符 (\\t) 替代空格缩进
  "vueIndentScriptAndStyle": false, // 缩进Vue文件中的 `<script>` 和 `<style>` 内容
  "overrides": [
    {
      "files": "*.md",
      "options": {
        "printWidth": 100,
        "proseWrap": "always"
      }
    }
  ] // 文件覆盖规则 (按模式自定义格式规则)
}
