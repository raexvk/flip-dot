# Flip Dot

Animated digit component simulating a physical flip-dot display. Dots flip with spring physics in a diagonal cascade pattern, creating a satisfying mechanical transition.

[Live Demo →](https://vbuilds.vercel.app/components/flip-dot)

## Usage

```tsx
import { FlipDot } from "./flip-dot";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <FlipDot value={digit} size={64} />;
}
```

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `value` | `number` | `0` | Digit to display (0–9) |
| `size` | `number` | `64` | Width in pixels. Height is 1.5× width. |

## Built With

- React
- Framer Motion
- TypeScript

## License

MIT
