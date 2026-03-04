# @raex-ui/flip-dot

A cascading dot-flip grid that simulates a physical flip-dot display. Dots flip with spring physics in a diagonal cascade pattern.

![flip-dot](https://raex-ui.vercel.app/components/flip-dot)

## Install

```bash
npm install @raex-ui/flip-dot
```

## Usage

```tsx
import { FlipDot } from "@raex-ui/flip-dot";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <FlipDot value={digit} size={64} />;
}
```

## Props

| Prop | Type | Description |
|------|------|-------------|
| `value` | `number` | Digit to display (0–9) |
| `size` | `number` | Width in pixels. Height is automatically 1.5× width. |

## Peer Dependencies

- `react` >=18
- `react-dom` >=18
- `framer-motion` >=10

No Tailwind CSS required.

## License

MIT
